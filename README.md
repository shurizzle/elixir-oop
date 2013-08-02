# OOP

FOR TEH LULZ

```elixir
use OOP

class LULZ do
  attr lulz
  attr_writer lol1
  attr_reader [lol2, :lol3]

  def initialize do
    @lulz = "STUFF"
    @lol1 = 1
    @lol2 = 2
    @lol3 = 3
  end
end

lulz = LULZ.new
lulz.lulz # "STUFF"
lulz.lulz("STAHP") # "STAHP"
lulz.lol1 # ** (UndefinedFunctionError) undefined function: LULZ.lol1/1
lulz.lol2 # 2
lulz.lol3 # 3
lulz.lol2("LOL") # ** (UndefinedFunctionError) undefined function: LULZ.lol2/2
```
