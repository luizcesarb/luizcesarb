```php
<?php

namespace Dev;

class About extends Me
{
    protected function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Brand Force Mastery',
                'position' => 'Front-End Developer'         
            ]
        ];
    }

    protected function getKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            APIRest::class,
            Javascript::class,
            React::class,
            Vuejs::class,
            Angular::class,
            Tailwindcss::class,
            SqlServer::class,
            PostgreSQL::class,
            Mysql::class,
            Nodejs::class,
            Azure::class,
            Firebase::class,
            Git::class,
            Github::class,
            PowerBi::class,
            Tableau::class,
            QlikSense::class,
            Scrum::class,
            Kanban::class,
            Lean::class,
            Miro::class,
            Jira::class,
            
        ];
    }

    protected function getContact(): array
    {
        return [
           'linkedin' => 'https://www.linkedin.com/in/luizcesarb/',
           'email' => 'naosalvar@pm.me',
           'webSite' => 'https://luizcesar.com.br/'
        ]
    }
}
```




