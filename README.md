
## Hi there, I'm Abdullah Iftikhar 👋
```php
<?php

namespace AbdullahIftikhar;

class About extends Me
{
    public function getBio(): string
    {
        return 'I m a software developer specializing in PHP Laravel and JavaScript.
                I develop modern technology web applications with popular frameworks like Laravel, Livewire, Vue.js.
                SaaS,
                Multi-Tenancy,
                E-Commerce,
                RestFull API
                I develop advanced software with software architectures.';
    } 

    public function getMore(): array
    {
        return [
            'work' => [
                'Full Stack Developer - Al-burraq Technologies',
                'Laravel Developer - JuexDeveloper (Handle API work for Mobile Apps)',
                'Laravel Developer - Einnovetion'
            ]
        ];
    }

    public function getCurrentState(): array 
    {
        return [
            'working_on' => [
                'careerfy.pk - A platform to facilitate hiring managers to pick talent from local market',
            ],
            'learning' => [
                'Advance Programing Techniques',
                'MEARN'
            ]
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
