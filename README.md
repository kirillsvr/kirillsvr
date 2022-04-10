![Header](https://github.com/kirillsvr/kirillsvr/raw/master/assets/banner.jpg)

<br>

Hi, I'm Kirill Bondarenko, a junior php developer 👨🏻‍💻. I am a person who admires the ability to transform the world with the help of code, with a growing love for kick ass products , clean code and algorithms. Besides Hacking stuff, I play chess ♘ 😎.

<br>

## How I'd define myself...literally

```php
namespace Kirillsvr\Kirillsvr;

class About extends Me
{
    public function getBackendKnowledge(): array
    {
        return [
            PHP::class,
            Laravel::class,
        ]   
    }
    
    public function getFrontendKnowledge(): array
    {
        return [
            HTML::class,
            CSS::class,
            Boostrap::class,
            JQuery::class,
        ]   
    }
    
    public function getDataBaseKnowledge(): array
    {
        return [
            MySQL::class,
            PostgeSQL::class,
            Mongo::class,
        ]   
    }
    
    public function getToolsKnowledge(): array
    {
        return [
            GIT::class,
            Docker::class,
            Nginx::class,
        ]   
    }
    
    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```