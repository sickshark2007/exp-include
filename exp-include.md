# exp-include
![image save](https://imgur.com/Ho2xaBP.png)

# How to use 
 Note: if any utility does not work correctly contact me

## Usage:
```pawn
#include <a_samp>
#include <exp>
#include <zcmd> //command's (it is not necessary for the include to work.)

main()
{
  print("Hello damn world !");
}

CMD:test(playerid)
{
  ExpFunc(playerid, GetPlayerScore(playerid), GetPlayerScore(playerid)+1, GetPlayerScore(playerid), 10);
  return true;
}
```
