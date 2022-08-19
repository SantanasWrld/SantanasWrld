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
```
