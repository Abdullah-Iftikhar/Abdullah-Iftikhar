
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
                'autotalk.ai - AI-based bots help to grow businesses.',
                'oblyalo.com - Entertainment platform'
            ],
            'learning' => [
                'Advance Programing Techniques',
                'AI',
                'Python'
            ]
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
```
