<?php

namespace Dev;

class About extends Me
{
    protected function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'ProjectOn',
                'position' => 'Full Stack Developer'         
            ]
        ];
    }

    protected function getKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            Javascript::class,
            React::class,
            Vuejs::class,
            Bootstrap::class,
            Tailwindcss::class,
            Api::class,
            SqlServer::class,
            PostgreSQL::class,
            Mysql::class,
            Nodejs::class,
            Azure::class,
            AWS::class,
            Firebase::class,
            Git::class,
            Github::class,
            PowerBi::class,
            Scrum::class,
            Kanban::class,
            Lean::class,
            Miro::class,
            Planner::class,
            
        ];
    }

    protected function getContact(): array
    {
        return [
           'linkedin' => 'https://www.linkedin.com/in/luizcesarb/',
           'email' => 'naosalvar@pm.me',
           'webSite' => 'https://luizcesar.com/'
        ]
    }
}





