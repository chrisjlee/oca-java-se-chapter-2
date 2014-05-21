##  Numeric Underscore Examples

### Which var incorrectly uses underscore rules?

        long var1 = 0_100_267_760;
        long var2 = 0_x_4_13;
        long var3 = 0b_x10_BA_75;
        long var4 = 0b_10000_10_11;
        long var5 = 0xa10_AG_75;
        long var6 = 0x1_0000_10;
        long var7 = 100__12_12;

<p class="fragment roll-in">Answer: <code>var2, var3, var4, var5</code></p>
<p class="fragment roll-in">Underscores should only be placed between digits.</p>

note:
    var2-5
    Underscores should only be placed between digits

    Open Eclipse example PrimitiveNumericsUnderscores
