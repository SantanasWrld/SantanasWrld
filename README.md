```php
<?php

declare(strict_types=1);

namespace SantanasWrld;

final class About extends Me
{
    /** @return array */
    protected function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Bushwick Commodity',
                'position' => 'Head of Product Management'
            ]
        ];
    }

    /** @return array */
    protected function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Python::class,
            Aws::class,
            Java::class,
            C::class
        ];
    }

    /** @return string */
    protected function getFutureGoal(): string
    {
        return 'To Contribute to Open Source Projects.';
    }
}
``
<h2>Listen Along <img align="right" alt="Profile Hits" src="https://komarev.com/ghpvc/?username=cheesits456&style=flat-square"></h2>

[![spotify-github-profile](https://spotify-github-profile.vercel.app/api/view?uid=2243oqpi3nzhicmyv3uuo3iuy&cover_image=true&theme=novatorem&bar_color=53b14f&bar_color_cover=false)](https://spotify-github-profile.vercel.app/api/view?uid=2243oqpi3nzhicmyv3uuo3iuy&redirect=true)
