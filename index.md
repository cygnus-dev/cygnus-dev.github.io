## Python01

its actually the first project i started, although it probably wont get anywhere. Written in python, its my first attempt at coding. While not well organised or even well coded, it gets the job done, as in it works. Will improve on this project, and maybe even completly revamp the messy code.

```python
async def run(ctx):
    random_index = randint(1, 100)
    luck = random_index
    unlucky_msg = "Too bad, landed sideways :("
    lucky_msg = "landed the right way up! very cool!"

    def bottle__flip():
        if luck > 15:
            return unlucky_msg
        else:
            return lucky_msg

    await ctx.send(bottle__flip())

```

please inform me if u have any suggestions or critisicm. All criticism is welcome. Repository: (https://github.com/cygnus-dev/python01)

## Java1

my first attempt at Java. just a couple of files with random tests. Again, expect bad code here since i still have no idea how object oriented programming works(although am figuring out). I will eventually begin a couple of projects on Java, not sure what tho.

```java
public class Bottleflip {
    public static void main(String[] args) {
        Random rand = new Random();
        int x = rand.nextInt(100);
        x += 1;

        if (x > 15) {
            boolean y = true;
            System.out.println("sory botle broek");
        } else {
            boolean y = false;
            System.out.println("Bootle landed uprigth!");
        }
    }
}
```

Again, critism welcome. Repository: (https://github.com/cygnus-dev/Java1)

## Contacts

If you want to contact me for whatever reason, here my discord - NotCygnusv#0905

apologies if I dont respond, which is highly likley.

-Cy

