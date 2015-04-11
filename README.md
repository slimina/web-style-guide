


<!DOCTYPE html>
<html lang="en" class="">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>javascript-style-guide/README.md at master · adamlu/javascript-style-guide</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="adamlu/javascript-style-guide" name="twitter:title" /><meta content="javascript-style-guide - JavaScript规范" name="twitter:description" /><meta content="https://avatars2.githubusercontent.com/u/92850?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars2.githubusercontent.com/u/92850?v=3&amp;s=400" property="og:image" /><meta content="adamlu/javascript-style-guide" property="og:title" /><meta content="https://github.com/adamlu/javascript-style-guide" property="og:url" /><meta content="javascript-style-guide - JavaScript规范" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/MTEyNDA0Mzc6MDk5ZGZjOGI4MGEyNzgxOWJlZDBiZDIyOTUyYWNmZDI6MTcwZGQ2NDJmMzMyMDlhYTgwZmIwMDc4OWY3ZDk1OTcyNWY2ZTY1ODgyOTliNjgzZWU0YWVjMzIyYzFiYmRmZg==--87152a6755de193400d719dcde0de6b436336110">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>
      <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="AF19BD2F:5905:1689831:5528BE7F" name="octolytics-dimension-request_id" /><meta content="11240437" name="octolytics-actor-id" /><meta content="slimina" name="octolytics-actor-login" /><meta content="084a50266c429ca0b0aef9504c25c5cb8ec8462ac0ab00305a6ca3137c5fecb1" name="octolytics-actor-hash" />
    
    <meta content="Rails, view, blob#show" name="analytics-event" />
    <meta class="js-ga-set" name="dimension1" content="Logged In">
    <meta class="js-ga-set" name="dimension2" content="Header v3">
    <meta name="is-dotcom" content="true">
    <meta name="hostname" content="github.com">
    <meta name="user-login" content="slimina">

    
    <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="oT5ovvXPvszDevbNZUnv8Y0Bd9ENKIwfNaazaaLgUW6NQuagMqU0aSE/WRrse7t3RIAhWWrE83/u/cO0mP8E2g==" name="csrf-token" />

    <link href="https://assets-cdn.github.com/assets/github-6a4174aa7e25ce4268078491fdfa22273eef841d99e1ab07ccce9b89c747f55d.css" media="all" rel="stylesheet" />
    <link href="https://assets-cdn.github.com/assets/github2-5b5e999e041f2586f9dc06b940229076225e6ec5ab5406be292a87331325fdc0.css" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="f227b009e29272e5bb7d2b5ef04d2783">

      
  <meta name="description" content="javascript-style-guide - JavaScript规范">
  <meta name="go-import" content="github.com/adamlu/javascript-style-guide git https://github.com/adamlu/javascript-style-guide.git">

  <meta content="92850" name="octolytics-dimension-user_id" /><meta content="adamlu" name="octolytics-dimension-user_login" /><meta content="11816219" name="octolytics-dimension-repository_id" /><meta content="adamlu/javascript-style-guide" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="11816219" name="octolytics-dimension-repository_network_root_id" /><meta content="adamlu/javascript-style-guide" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/adamlu/javascript-style-guide/commits/master.atom" rel="alternate" title="Recent Commits to javascript-style-guide:master" type="application/atom+xml">

  </head>


  <body class="logged_in  env-production windows vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      


        <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github"></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <form accept-charset="UTF-8" action="/adamlu/javascript-style-guide/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/adamlu/javascript-style-guide/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <input type="text"
    class="js-site-search-field is-clearable"
    data-hotkey="s"
    name="q"
    placeholder="Search"
    data-global-scope-placeholder="Search GitHub"
    data-repo-scope-placeholder="Search"
    tabindex="1"
    autocapitalize="off">
  <div class="scope-badge">This repository</div>
</form>
      </div>

      <ul class="header-nav left" role="navigation">
          <li class="header-nav-item explore">
            <a class="header-nav-link" href="/explore" data-ga-click="Header, go to explore, text:explore">Explore</a>
          </li>
            <li class="header-nav-item">
              <a class="header-nav-link" href="https://gist.github.com" data-ga-click="Header, go to gist, text:gist">Gist</a>
            </li>
            <li class="header-nav-item">
              <a class="header-nav-link" href="/blog" data-ga-click="Header, go to blog, text:blog">Blog</a>
            </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
          </li>
      </ul>

      
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name" href="/slimina" data-ga-click="Header, go to profile, text:username">
      <img alt="@slimina" class="avatar" data-user="11240437" height="20" src="https://avatars1.githubusercontent.com/u/11240437?v=3&amp;s=40" width="20" />
      <span class="css-truncate">
        <span class="css-truncate-target">slimina</span>
      </span>
    </a>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link js-menu-target tooltipped tooltipped-s" href="/new" aria-label="Create new..." data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu">
        
<li>
  <a href="/new" data-ga-click="Header, create new repository, icon:repo"><span class="octicon octicon-repo"></span> New repository</a>
</li>
<li>
  <a href="/organizations/new" data-ga-click="Header, create new organization, icon:organization"><span class="octicon octicon-organization"></span> New organization</a>
</li>


  <li class="dropdown-divider"></li>
  <li class="dropdown-header">
    <span title="adamlu/javascript-style-guide">This repository</span>
  </li>
    <li>
      <a href="/adamlu/javascript-style-guide/issues/new" data-ga-click="Header, create new issue, icon:issue"><span class="octicon octicon-issue-opened"></span> New issue</a>
    </li>

      </ul>
    </div>
  </li>

  <li class="header-nav-item">
        <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
        <span class="mail-status all-read"></span>
        <span class="octicon octicon-inbox"></span>
</a>
  </li>

  <li class="header-nav-item">
    <a class="header-nav-link tooltipped tooltipped-s" href="/settings/profile" id="account_settings" aria-label="Settings" data-ga-click="Header, go to settings, icon:settings">
      <span class="octicon octicon-gear"></span>
    </a>
  </li>

  <li class="header-nav-item">
    <form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="NNA2TxxKKsMUOaFUpvkzVUUFglrmdYQEgiiKxGbht/jZuuvXUlI8yHRRO51ZWwVDWkB8SIuoF3YFuohLV0T8rg==" /></div>
      <button class="header-nav-link sign-out-button tooltipped tooltipped-s" aria-label="Sign out" data-ga-click="Header, sign out, icon:logout">
        <span class="octicon octicon-sign-out"></span>
      </button>
</form>  </li>

</ul>



    
  </div>
</div>

        

        
<div class="flash-global js-notice flash-warn">
<div class="container">
    <h2>
      You don't have any verified emails.  We recommend <a href="https://github.com/settings/emails">verifying</a> at least one email.
    </h2>
    <p>
Email verification helps our support team verify ownership if you lose account access and allows you to receive all the notifications you ask for.
    </p>



















</div>
</div>


      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    <div id="js-flash-container">
      
    </div>
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">
        
<ul class="pagehead-actions">

  <li>
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="LAJap3Pemh3Lf9qzqwyjbHkkdAfik4UeIPfVw+wpsKzyzyE9EC2l5e6kKhuaOvSkGfKF7bjH7eUnpaq4P9+/bw==" /></div>    <input id="repository_id" name="repository_id" type="hidden" value="11816219" />

      <div class="select-menu js-menu-container js-select-menu">
        <a href="/adamlu/javascript-style-guide/subscription"
          class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
          data-ga-click="Repository, click Watch settings, action:blob#show">
          <span class="js-select-button">
            <span class="octicon octicon-eye"></span>
            Watch
          </span>
        </a>
        <a class="social-count js-social-count" href="/adamlu/javascript-style-guide/watchers">
          33
        </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header">
              <span class="select-menu-title">Notifications</span>
              <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
            </div>

            <div class="select-menu-list js-navigation-container" role="menu">

              <div class="select-menu-item js-navigation-item selected" role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input checked="checked" id="do_included" name="do" type="radio" value="included" />
                  <span class="select-menu-item-heading">Not watching</span>
                  <span class="description">Be notified when participating or @mentioned.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Watch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_subscribed" name="do" type="radio" value="subscribed" />
                  <span class="select-menu-item-heading">Watching</span>
                  <span class="description">Be notified of all conversations.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-eye"></span>
                    Unwatch
                  </span>
                </div>
              </div>

              <div class="select-menu-item js-navigation-item " role="menuitem" tabindex="0">
                <span class="select-menu-item-icon octicon octicon-check"></span>
                <div class="select-menu-item-text">
                  <input id="do_ignore" name="do" type="radio" value="ignore" />
                  <span class="select-menu-item-heading">Ignoring</span>
                  <span class="description">Never be notified.</span>
                  <span class="js-select-button-text hidden-select-button-text">
                    <span class="octicon octicon-mute"></span>
                    Stop ignoring
                  </span>
                </div>
              </div>

            </div>

          </div>
        </div>
      </div>
</form>
  </li>

  <li>
    
  <div class="js-toggler-container js-social-container starring-container ">

    <form accept-charset="UTF-8" action="/adamlu/javascript-style-guide/unstar" class="js-toggler-form starred js-unstar-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="5XhGS1YGoSr9a3AKzxZIZK+b1hBtfdbSAdEbFY/A8LT1rY5jxrZEJP1Cdq4ZtV7WRnYjvr3JT8axhqNszONLTQ==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar adamlu/javascript-style-guide"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <span class="octicon octicon-star"></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/adamlu/javascript-style-guide/stargazers">
          250
        </a>
</form>
    <form accept-charset="UTF-8" action="/adamlu/javascript-style-guide/star" class="js-toggler-form unstarred js-star-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="1L++ZOYlo2awp4pbclo5B9VoTlNrx0Y8mS5YlylebTwlbDBsRBkThq94KtZQoC3bKCNRuCI+nQbfLV8HiCnR1w==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star adamlu/javascript-style-guide"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <span class="octicon octicon-star"></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/adamlu/javascript-style-guide/stargazers">
          250
        </a>
</form>  </div>

  </li>

        <li>
          <form accept-charset="UTF-8" action="/adamlu/javascript-style-guide/fork" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="UnSfHRsVQ3He2hF7AaLuGauAeOXiFHPIgXI+HWDM6GbB2M7FJJx9jDF2GZaFDr9OlqJoAmlIH8PFXYFiPUCv0A==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of adamlu/javascript-style-guide to your account"
                aria-label="Fork your own copy of adamlu/javascript-style-guide to your account">
              <span class="octicon octicon-repo-forked"></span>
              Fork
            </button>
            <a href="/adamlu/javascript-style-guide/network" class="social-count">106</a>
</form>        </li>

</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo"></span>
          <span class="author"><a href="/adamlu" class="url fn" itemprop="url" rel="author"><span itemprop="title">adamlu</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/adamlu/javascript-style-guide" class="js-current-repository" data-pjax="#js-repo-pjax-container">javascript-style-guide</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
          </span>

        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline  ">
        <div class="repository-sidebar clearfix">
            
<nav class="sunken-menu repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container"
     data-issue-count-url="/adamlu/javascript-style-guide/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/adamlu/javascript-style-guide" aria-label="Code" class="selected js-selected-navigation-item sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /adamlu/javascript-style-guide">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Issues">
        <a href="/adamlu/javascript-style-guide/issues" aria-label="Issues" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /adamlu/javascript-style-guide/issues">
          <span class="octicon octicon-issue-opened"></span> <span class="full-word">Issues</span>
          <span class="js-issue-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>      </li>

    <li class="tooltipped tooltipped-w" aria-label="Pull requests">
      <a href="/adamlu/javascript-style-guide/pulls" aria-label="Pull requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /adamlu/javascript-style-guide/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

      <li class="tooltipped tooltipped-w" aria-label="Wiki">
        <a href="/adamlu/javascript-style-guide/wiki" aria-label="Wiki" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g w" data-selected-links="repo_wiki /adamlu/javascript-style-guide/wiki">
          <span class="octicon octicon-book"></span> <span class="full-word">Wiki</span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>      </li>
  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/adamlu/javascript-style-guide/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /adamlu/javascript-style-guide/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/adamlu/javascript-style-guide/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /adamlu/javascript-style-guide/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>
  </ul>


</nav>

              <div class="only-with-full-nav">
                  
<div class="clone-url open"
  data-protocol-type="http"
  data-url="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/adamlu/javascript-style-guide.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" data-copy-hint="Copy to clipboard" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="ssh"
  data-url="/users/set_protocol?protocol_selector=ssh&amp;protocol_type=clone">
  <h3><span class="text-emphasized">SSH</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="git@github.com:adamlu/javascript-style-guide.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" data-copy-hint="Copy to clipboard" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="subversion"
  data-url="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/adamlu/javascript-style-guide" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" data-copy-hint="Copy to clipboard" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<p class="clone-options">You can clone with
  <a href="#" class="js-clone-selector" data-protocol="http">HTTPS</a>, <a href="#" class="js-clone-selector" data-protocol="ssh">SSH</a>, or <a href="#" class="js-clone-selector" data-protocol="subversion">Subversion</a>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</p>


  <a href="https://windows.github.com" class="btn btn-sm sidebar-button" title="Save adamlu/javascript-style-guide to your computer and use it in GitHub Desktop." aria-label="Save adamlu/javascript-style-guide to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>


                <a href="/adamlu/javascript-style-guide/archive/master.zip"
                   class="btn btn-sm sidebar-button"
                   aria-label="Download the contents of adamlu/javascript-style-guide as a zip file"
                   title="Download the contents of adamlu/javascript-style-guide as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>
          

<a href="/adamlu/javascript-style-guide/blob/3d67486fdaf6b8f6c1cc013c9e60ba1ee518b75b/README.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:b0dd10dfb28f36557a5f8d08dd0b19b0 -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-master-branch="master"
    data-ref="master"
    title="master"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/adamlu/javascript-style-guide/blob/master/README.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

  <div class="btn-group right">
    <a href="/adamlu/javascript-style-guide/find/master"
          class="js-show-file-finder btn btn-sm empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" data-copy-hint="Copy file path to clipboard" type="button"><span class="octicon octicon-clippy"></span></button>
  </div>

  <div class="breadcrumb js-zeroclipboard-target">
    <span class='repo-root js-repo-root'><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/adamlu/javascript-style-guide" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">javascript-style-guide</span></a></span></span><span class="separator">/</span><strong class="final-path">README.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="@adamlu" class="avatar" data-user="92850" height="24" src="https://avatars3.githubusercontent.com/u/92850?v=3&amp;s=48" width="24" />
        <span class="author"><a href="/adamlu" rel="author">adamlu</a></span>
        <time datetime="2014-05-28T07:31:52Z" is="relative-time">May 28, 2014</time>
        <div class="commit-title">
            <a href="/adamlu/javascript-style-guide/commit/3d67486fdaf6b8f6c1cc013c9e60ba1ee518b75b" class="message" data-pjax="true" title="Update README.md">Update README.md</a>
        </div>
    </div>

    <div class="participation">
      <p class="quickstat">
        <a href="#blob_contributors_box" rel="facebox">
          <strong>1</strong>
           contributor
        </a>
      </p>
      
    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list">
          <li class="facebox-user-list-item">
            <img alt="@adamlu" data-user="92850" height="24" src="https://avatars3.githubusercontent.com/u/92850?v=3&amp;s=48" width="24" />
            <a href="/adamlu">adamlu</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
    <div class="file-actions">

      <div class="btn-group">
        <a href="/adamlu/javascript-style-guide/raw/master/README.md" class="btn btn-sm " id="raw-url">Raw</a>
          <a href="/adamlu/javascript-style-guide/blame/master/README.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
        <a href="/adamlu/javascript-style-guide/commits/master/README.md" class="btn btn-sm " rel="nofollow">History</a>
      </div>

        <a class="octicon-btn tooltipped tooltipped-nw"
           href="https://windows.github.com"
           aria-label="Open this file in GitHub for Windows">
            <span class="octicon octicon-device-desktop"></span>
        </a>

            <form accept-charset="UTF-8" action="/adamlu/javascript-style-guide/edit/master/README.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="CW+KJ3ZDu4IWKwgX9591vBJWGIXzJmXtC49LFJf6WIxTDx/LvjXO9pCcbhsFPvh7c+37AoWPIpBbh50STQ8PUQ==" /></div>
              <button class="octicon-btn tooltipped tooltipped-n" type="submit" aria-label="Clicking this button will fork this project so you can edit the file" data-hotkey="e" data-disable-with>
                <span class="octicon octicon-pencil"></span>
              </button>
</form>
          <form accept-charset="UTF-8" action="/adamlu/javascript-style-guide/delete/master/README.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="EYhA0lQKTSZfrSY6x2T9oUEljmdDekwM6xoW+5nGueEF2sw0amqwzu+tayQdk6JpzrtBCzPQqkWxX4ug9HZ3yg==" /></div>
            <button class="octicon-btn octicon-btn-danger tooltipped tooltipped-n" type="submit" aria-label="Fork this project and delete file" data-disable-with>
              <span class="octicon octicon-trashcan"></span>
            </button>
</form>    </div>

    <div class="file-info">
        1329 lines (974 sloc)
        <span class="file-info-divider"></span>
      31.072 kb
    </div>
  </div>
    <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><p><a href="https://github.com/airbnb/javascript">原文: https://github.com/airbnb/javascript</a></p>

<p>注：本人根据自己的开发习惯删除和修改了部分规范</p>

<h1>
<a id="user-content-javascript规范" class="anchor" href="#javascript%E8%A7%84%E8%8C%83" aria-hidden="true"><span class="octicon octicon-link"></span></a>JavaScript规范</h1>

<h2>
<a id="user-content-内容列表" class="anchor" href="#%E5%86%85%E5%AE%B9%E5%88%97%E8%A1%A8" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-TOC">内容列表</a>
</h2>

<ol class="task-list">
<li><a href="#types">类型</a></li>
<li><a href="#objects">对象</a></li>
<li><a href="#arrays">数组</a></li>
<li><a href="#strings">字符串</a></li>
<li><a href="#functions">函数</a></li>
<li><a href="#properties">属性</a></li>
<li><a href="#variables">变量</a></li>
<li><a href="#conditionals">条件表达式和等号</a></li>
<li><a href="#blocks">块</a></li>
<li><a href="#comments">注释</a></li>
<li><a href="#whitespace">空白</a></li>
<li><a href="#commas">逗号</a></li>
<li><a href="#semicolons">分号</a></li>
<li><a href="#type-coercion">类型转换</a></li>
<li><a href="#naming-conventions">命名约定</a></li>
<li><a href="#accessors">存取器</a></li>
<li><a href="#constructors">构造器</a></li>
<li><a href="#events">事件</a></li>
<li><a href="#modules">模块</a></li>
<li><a href="#jquery">jQuery</a></li>
<li><a href="#es5">ES5 兼容性</a></li>
<li><a href="#performance">性能</a></li>
<li><a href="#resources">资源</a></li>
<li><a href="#in-the-wild">哪些人在使用</a></li>
<li><a href="#translation">翻译</a></li>
<li><a href="#guide-guide">JavaScript风格指南</a></li>
<li><a href="#contributors">贡献者</a></li>
<li><a href="#license">许可</a></li>
</ol>

<h2>
<a id="user-content-类型" class="anchor" href="#%E7%B1%BB%E5%9E%8B" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-types">类型</a>
</h2>

<ul class="task-list">
<li>
<p><strong>原始值</strong>: 相当于传值</p>

<ul class="task-list">
<li><code>string</code></li>
<li><code>number</code></li>
<li><code>boolean</code></li>
<li><code>null</code></li>
<li><code>undefined</code></li>
</ul>

<div class="highlight highlight-javascript"><pre><span class="pl-k">var</span> foo <span class="pl-k">=</span> <span class="pl-c1">1</span>,
    bar <span class="pl-k">=</span> foo;

bar <span class="pl-k">=</span> <span class="pl-c1">9</span>;

<span class="pl-en">console</span><span class="pl-c1">.log</span>(foo, bar); <span class="pl-c">// =&gt; 1, 9</span></pre></div>
</li>
<li>
<p><strong>复杂类型</strong>: 相当于传引用</p>

<ul class="task-list">
<li><code>object</code></li>
<li><code>array</code></li>
<li><code>function</code></li>
</ul>

<div class="highlight highlight-javascript"><pre><span class="pl-k">var</span> foo <span class="pl-k">=</span> [<span class="pl-c1">1</span>, <span class="pl-c1">2</span>],
    bar <span class="pl-k">=</span> foo;

bar[<span class="pl-c1">0</span>] <span class="pl-k">=</span> <span class="pl-c1">9</span>;

<span class="pl-en">console</span><span class="pl-c1">.log</span>(foo[<span class="pl-c1">0</span>], bar[<span class="pl-c1">0</span>]); <span class="pl-c">// =&gt; 9, 9</span></pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-对象" class="anchor" href="#%E5%AF%B9%E8%B1%A1" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-objects">对象</a>
</h2>

<ul class="task-list">
<li>
<p>使用字面值创建对象</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">var</span> item <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">Object</span>();

<span class="pl-c">// good</span>
<span class="pl-k">var</span> item <span class="pl-k">=</span> {};</pre></div>
</li>
<li>
<p>不要使用保留字 <a href="https://developer.mozilla.org/en-US/docs/JavaScript/Reference/Reserved_Words">reserved words</a> 作为键</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">var</span> superman <span class="pl-k">=</span> {
  class<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>superhero<span class="pl-pds">'</span></span>,
  <span class="pl-k">default</span><span class="pl-k">:</span> { clark<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>kent<span class="pl-pds">'</span></span> },
  private<span class="pl-k">:</span> <span class="pl-c1">true</span>
};

<span class="pl-c">// good</span>
<span class="pl-k">var</span> superman <span class="pl-k">=</span> {
  klass<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>superhero<span class="pl-pds">'</span></span>,
  defaults<span class="pl-k">:</span> { clark<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>kent<span class="pl-pds">'</span></span> },
  hidden<span class="pl-k">:</span> <span class="pl-c1">true</span>
};</pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-数组" class="anchor" href="#%E6%95%B0%E7%BB%84" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-arrays">数组</a>
</h2>

<ul class="task-list">
<li>
<p>使用字面值创建数组</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">var</span> items <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">Array</span>();

<span class="pl-c">// good</span>
<span class="pl-k">var</span> items <span class="pl-k">=</span> [];</pre></div>
</li>
<li>
<p>如果你不知道数组的长度，使用push</p>

<div class="highlight highlight-javascript"><pre><span class="pl-k">var</span> someStack <span class="pl-k">=</span> [];


<span class="pl-c">// bad</span>
someStack[someStack.<span class="pl-c1">length</span>] <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>abracadabra<span class="pl-pds">'</span></span>;

<span class="pl-c">// good</span>
someStack.<span class="pl-c1">push</span>(<span class="pl-s"><span class="pl-pds">'</span>abracadabra<span class="pl-pds">'</span></span>);</pre></div>
</li>
<li>
<p>当你需要拷贝数组时使用slice. <a href="http://jsperf.com/converting-arguments-to-an-array/7">jsPerf</a></p>

<div class="highlight highlight-javascript"><pre><span class="pl-k">var</span> len <span class="pl-k">=</span> items.<span class="pl-c1">length</span>,
    itemsCopy <span class="pl-k">=</span> [],
    i;

<span class="pl-c">// bad</span>
<span class="pl-k">for</span> (i <span class="pl-k">=</span> <span class="pl-c1">0</span>; i <span class="pl-k">&lt;</span> len; i<span class="pl-k">++</span>) {
  itemsCopy[i] <span class="pl-k">=</span> items[i];
}

<span class="pl-c">// good</span>
itemsCopy <span class="pl-k">=</span> items.<span class="pl-c1">slice</span>();</pre></div>
</li>
<li>
<p>使用slice将类数组的对象转成数组.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-k">function</span> <span class="pl-en">trigger</span>() {
  <span class="pl-k">var</span> args <span class="pl-k">=</span> <span class="pl-c1">Array</span>.<span class="pl-c1">prototype</span>.slice.<span class="pl-c1">call</span>(arguments);
  ...
}</pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-字符串" class="anchor" href="#%E5%AD%97%E7%AC%A6%E4%B8%B2" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-strings">字符串</a>
</h2>

<ul class="task-list">
<li>
<p>对字符串使用单引号 <code>''</code></p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">var</span> name <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Bob Parr<span class="pl-pds">"</span></span>;

<span class="pl-c">// good</span>
<span class="pl-k">var</span> name <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>Bob Parr<span class="pl-pds">'</span></span>;

<span class="pl-c">// bad</span>
<span class="pl-k">var</span> fullName <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>Bob <span class="pl-pds">"</span></span> <span class="pl-k">+</span> <span class="pl-v">this</span>.lastName;

<span class="pl-c">// good</span>
<span class="pl-k">var</span> fullName <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>Bob <span class="pl-pds">'</span></span> <span class="pl-k">+</span> <span class="pl-v">this</span>.lastName;</pre></div>
</li>
<li><p>超过80个字符的字符串应该使用字符串连接换行</p></li>
<li>
<p>注: 如果过度使用，长字符串连接可能会对性能有影响. <a href="http://jsperf.com/ya-string-concat">jsPerf</a> &amp; <a href="https://github.com/airbnb/javascript/issues/40">Discussion</a></p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">var</span> errorMessage <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>This is a super long error that was thrown because of Batman. When you stop to think about how Batman had anything to do with this, you would get nowhere fast.<span class="pl-pds">'</span></span>;

<span class="pl-c">// bad</span>
<span class="pl-k">var</span> errorMessage <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>This is a super long error that \</span>
<span class="pl-s">was thrown because of Batman. \</span>
<span class="pl-s">When you stop to think about \</span>
<span class="pl-s">how Batman had anything to do \</span>
<span class="pl-s">with this, you would get nowhere \</span>
<span class="pl-s">fast.<span class="pl-pds">'</span></span>;


<span class="pl-c">// good</span>
<span class="pl-k">var</span> errorMessage <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>This is a super long error that <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
  <span class="pl-s"><span class="pl-pds">'</span>was thrown because of Batman.<span class="pl-pds">'</span></span> <span class="pl-k">+</span>
  <span class="pl-s"><span class="pl-pds">'</span>When you stop to think about <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
  <span class="pl-s"><span class="pl-pds">'</span>how Batman had anything to do <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
  <span class="pl-s"><span class="pl-pds">'</span>with this, you would get nowhere <span class="pl-pds">'</span></span> <span class="pl-k">+</span>
  <span class="pl-s"><span class="pl-pds">'</span>fast.<span class="pl-pds">'</span></span>;</pre></div>
</li>
<li>
<p>编程时使用join而不是字符串连接来构建字符串，特别是IE: <a href="http://jsperf.com/string-vs-array-concat/2">jsPerf</a>.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-k">var</span> items,
    messages,
    length, i;

messages <span class="pl-k">=</span> [{
    state<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>success<span class="pl-pds">'</span></span>,
    message<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>This one worked.<span class="pl-pds">'</span></span>
},{
    state<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>success<span class="pl-pds">'</span></span>,
    message<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>This one worked as well.<span class="pl-pds">'</span></span>
},{
    state<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>error<span class="pl-pds">'</span></span>,
    message<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>This one did not work.<span class="pl-pds">'</span></span>
}];

length <span class="pl-k">=</span> messages.<span class="pl-c1">length</span>;

<span class="pl-c">// bad</span>
<span class="pl-k">function</span> <span class="pl-en">inbox</span>(<span class="pl-smi">messages</span>) {
  items <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>&lt;ul&gt;<span class="pl-pds">'</span></span>;

  <span class="pl-k">for</span> (i <span class="pl-k">=</span> <span class="pl-c1">0</span>; i <span class="pl-k">&lt;</span> length; i<span class="pl-k">++</span>) {
    items <span class="pl-k">+=</span> <span class="pl-s"><span class="pl-pds">'</span>&lt;li&gt;<span class="pl-pds">'</span></span> <span class="pl-k">+</span> messages[i].message <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span>&lt;/li&gt;<span class="pl-pds">'</span></span>;
  }

  <span class="pl-k">return</span> items <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span>&lt;/ul&gt;<span class="pl-pds">'</span></span>;
}

<span class="pl-c">// good</span>
<span class="pl-k">function</span> <span class="pl-en">inbox</span>(<span class="pl-smi">messages</span>) {
  items <span class="pl-k">=</span> [];

  <span class="pl-k">for</span> (i <span class="pl-k">=</span> <span class="pl-c1">0</span>; i <span class="pl-k">&lt;</span> length; i<span class="pl-k">++</span>) {
    items[i] <span class="pl-k">=</span> messages[i].message;
  }

  <span class="pl-k">return</span> <span class="pl-s"><span class="pl-pds">'</span>&lt;ul&gt;&lt;li&gt;<span class="pl-pds">'</span></span> <span class="pl-k">+</span> items.<span class="pl-c1">join</span>(<span class="pl-s"><span class="pl-pds">'</span>&lt;/li&gt;&lt;li&gt;<span class="pl-pds">'</span></span>) <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span>&lt;/li&gt;&lt;/ul&gt;<span class="pl-pds">'</span></span>;
}</pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-函数" class="anchor" href="#%E5%87%BD%E6%95%B0" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-functions">函数</a>
</h2>

<ul class="task-list">
<li>
<p>函数表达式:</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// 匿名函数表达式</span>
<span class="pl-k">var</span> <span class="pl-en">anonymous</span> <span class="pl-k">=</span> <span class="pl-k">function</span>() {
  <span class="pl-k">return</span> <span class="pl-c1">true</span>;
};

<span class="pl-c">// 有名函数表达式</span>
<span class="pl-k">var</span> <span class="pl-en">named</span> <span class="pl-k">=</span> <span class="pl-k">function</span> <span class="pl-en">named</span>() {
  <span class="pl-k">return</span> <span class="pl-c1">true</span>;
};

<span class="pl-c">// 立即调用函数表达式</span>
(<span class="pl-k">function</span>() {
  <span class="pl-en">console</span><span class="pl-c1">.log</span>(<span class="pl-s"><span class="pl-pds">'</span>Welcome to the Internet. Please follow me.<span class="pl-pds">'</span></span>);
})();</pre></div>
</li>
<li><p>绝对不要在一个非函数块里声明一个函数，把那个函数赋给一个变量。浏览器允许你这么做，但是它们解析不同。</p></li>
<li>
<p><strong>注:</strong> ECMA-262定义把<code>块</code>定义为一组语句，函数声明不是一个语句。<a href="http://www.ecma-international.org/publications/files/ECMA-ST/Ecma-262.pdf#page=97">阅读ECMA-262对这个问题的说明</a>.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">if</span> (currentUser) {
  <span class="pl-k">function</span> <span class="pl-en">test</span>() {
    <span class="pl-en">console</span><span class="pl-c1">.log</span>(<span class="pl-s"><span class="pl-pds">'</span>Nope.<span class="pl-pds">'</span></span>);
  }
}

<span class="pl-c">// good</span>
<span class="pl-k">if</span> (currentUser) {
  <span class="pl-k">var</span> <span class="pl-en">test</span> <span class="pl-k">=</span> <span class="pl-k">function</span> <span class="pl-en">test</span>() {
    <span class="pl-en">console</span><span class="pl-c1">.log</span>(<span class="pl-s"><span class="pl-pds">'</span>Yup.<span class="pl-pds">'</span></span>);
  };
}</pre></div>
</li>
<li>
<p>绝对不要把参数命名为 <code>arguments</code>, 这将会逾越函数作用域内传过来的 <code>arguments</code> 对象.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">function</span> <span class="pl-en">nope</span>(<span class="pl-smi">name</span>, <span class="pl-smi">options</span>, <span class="pl-smi">arguments</span>) {
  <span class="pl-c">// ...stuff...</span>
}

<span class="pl-c">// good</span>
<span class="pl-k">function</span> <span class="pl-en">yup</span>(<span class="pl-smi">name</span>, <span class="pl-smi">options</span>, <span class="pl-smi">args</span>) {
  <span class="pl-c">// ...stuff...</span>
}</pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-属性" class="anchor" href="#%E5%B1%9E%E6%80%A7" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-properties">属性</a>
</h2>

<ul class="task-list">
<li>
<p>当使用变量访问属性时使用中括号.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-k">var</span> luke <span class="pl-k">=</span> {
  jedi<span class="pl-k">:</span> <span class="pl-c1">true</span>,
  age<span class="pl-k">:</span> <span class="pl-c1">28</span>
};

<span class="pl-k">function</span> <span class="pl-en">getProp</span>(<span class="pl-smi">prop</span>) {
  <span class="pl-k">return</span> luke[prop];
}

<span class="pl-k">var</span> isJedi <span class="pl-k">=</span> getProp(<span class="pl-s"><span class="pl-pds">'</span>jedi<span class="pl-pds">'</span></span>);</pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-变量" class="anchor" href="#%E5%8F%98%E9%87%8F" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-variables">变量</a>
</h2>

<ul class="task-list">
<li>
<p>总是使用 <code>var</code> 来声明变量，如果不这么做将导致产生全局变量，我们要避免污染全局命名空间。</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
superPower <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">SuperPower</span>();

<span class="pl-c">// good</span>
<span class="pl-k">var</span> superPower <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">SuperPower</span>();</pre></div>
</li>
<li>
<p>使用一个 <code>var</code> 以及新行声明多个变量，缩进4个空格。</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">var</span> items <span class="pl-k">=</span> getItems();
<span class="pl-k">var</span> goSportsTeam <span class="pl-k">=</span> <span class="pl-c1">true</span>;
<span class="pl-k">var</span> dragonball <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>z<span class="pl-pds">'</span></span>;

<span class="pl-c">// good</span>
<span class="pl-k">var</span> items <span class="pl-k">=</span> getItems(),
    goSportsTeam <span class="pl-k">=</span> <span class="pl-c1">true</span>,
    dragonball <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>z<span class="pl-pds">'</span></span>;</pre></div>
</li>
<li>
<p>最后再声明未赋值的变量，当你想引用之前已赋值变量的时候很有用。</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">var</span> i, len, dragonball,
    items <span class="pl-k">=</span> getItems(),
    goSportsTeam <span class="pl-k">=</span> <span class="pl-c1">true</span>;

<span class="pl-c">// bad</span>
<span class="pl-k">var</span> i, items <span class="pl-k">=</span> getItems(),
    dragonball,
    goSportsTeam <span class="pl-k">=</span> <span class="pl-c1">true</span>,
    len;

<span class="pl-c">// good</span>
<span class="pl-k">var</span> items <span class="pl-k">=</span> getItems(),
    goSportsTeam <span class="pl-k">=</span> <span class="pl-c1">true</span>,
    dragonball,
    length,
    i;</pre></div>
</li>
<li>
<p>在作用域顶部声明变量，避免变量声明和赋值引起的相关问题。</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">function</span>() {
  <span class="pl-c1">test</span>();
  <span class="pl-en">console</span><span class="pl-c1">.log</span>(<span class="pl-s"><span class="pl-pds">'</span>doing stuff..<span class="pl-pds">'</span></span>);

  <span class="pl-c">//..other stuff..</span>

  <span class="pl-k">var</span> name <span class="pl-k">=</span> getName();

  <span class="pl-k">if</span> (name <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">'</span>test<span class="pl-pds">'</span></span>) {
    <span class="pl-k">return</span> <span class="pl-c1">false</span>;
  }

  <span class="pl-k">return</span> name;
}

<span class="pl-c">// good</span>
<span class="pl-k">function</span>() {
  <span class="pl-k">var</span> name <span class="pl-k">=</span> getName();

  <span class="pl-c1">test</span>();
  <span class="pl-en">console</span><span class="pl-c1">.log</span>(<span class="pl-s"><span class="pl-pds">'</span>doing stuff..<span class="pl-pds">'</span></span>);

  <span class="pl-c">//..other stuff..</span>

  <span class="pl-k">if</span> (name <span class="pl-k">===</span> <span class="pl-s"><span class="pl-pds">'</span>test<span class="pl-pds">'</span></span>) {
    <span class="pl-k">return</span> <span class="pl-c1">false</span>;
  }

  <span class="pl-k">return</span> name;
}

<span class="pl-c">// bad</span>
<span class="pl-k">function</span>() {
  <span class="pl-k">var</span> name <span class="pl-k">=</span> getName();

  <span class="pl-k">if</span> (<span class="pl-k">!</span>arguments.<span class="pl-c1">length</span>) {
    <span class="pl-k">return</span> <span class="pl-c1">false</span>;
  }

  <span class="pl-k">return</span> <span class="pl-c1">true</span>;
}

<span class="pl-c">// good</span>
<span class="pl-k">function</span>() {
  <span class="pl-k">if</span> (<span class="pl-k">!</span>arguments.<span class="pl-c1">length</span>) {
    <span class="pl-k">return</span> <span class="pl-c1">false</span>;
  }

  <span class="pl-k">var</span> name <span class="pl-k">=</span> getName();

  <span class="pl-k">return</span> <span class="pl-c1">true</span>;
}</pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-条件表达式和等号" class="anchor" href="#%E6%9D%A1%E4%BB%B6%E8%A1%A8%E8%BE%BE%E5%BC%8F%E5%92%8C%E7%AD%89%E5%8F%B7" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-conditionals">条件表达式和等号</a>
</h2>

<ul class="task-list">
<li>适当使用 <code>===</code> 和 <code>!==</code> 以及 <code>==</code> 和 <code>!=</code>.</li>
<li>
<p>条件表达式的强制类型转换遵循以下规则：</p>

<ul class="task-list">
<li>
<strong>对象</strong> 被计算为 <strong>true</strong>
</li>
<li>
<strong>Undefined</strong> 被计算为 <strong>false</strong>
</li>
<li>
<strong>Null</strong> 被计算为 <strong>false</strong>
</li>
<li>
<strong>布尔值</strong> 被计算为 <strong>布尔的值</strong>
</li>
<li>
<strong>数字</strong> 如果是 <strong>+0, -0, or NaN</strong> 被计算为 <strong>false</strong> , 否则为 <strong>true</strong>
</li>
<li>
<strong>字符串</strong> 如果是空字符串 <code>''</code> 则被计算为 <strong>false</strong>, 否则为 <strong>true</strong>
</li>
</ul>

<div class="highlight highlight-javascript"><pre><span class="pl-k">if</span> ([<span class="pl-c1">0</span>]) {
  <span class="pl-c">// true</span>
  <span class="pl-c">// An array is an object, objects evaluate to true</span>
}</pre></div>
</li>
<li>
<p>使用快捷方式.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">if</span> (name <span class="pl-k">!==</span> <span class="pl-s"><span class="pl-pds">'</span><span class="pl-pds">'</span></span>) {
  <span class="pl-c">// ...stuff...</span>
}

<span class="pl-c">// good</span>
<span class="pl-k">if</span> (name) {
  <span class="pl-c">// ...stuff...</span>
}

<span class="pl-c">// bad</span>
<span class="pl-k">if</span> (collection.<span class="pl-c1">length</span> <span class="pl-k">&gt;</span> <span class="pl-c1">0</span>) {
  <span class="pl-c">// ...stuff...</span>
}

<span class="pl-c">// good</span>
<span class="pl-k">if</span> (collection.<span class="pl-c1">length</span>) {
  <span class="pl-c">// ...stuff...</span>
}</pre></div>
</li>
<li>
<p>阅读 <a href="http://javascriptweblog.wordpress.com/2011/02/07/truth-equality-and-javascript/#more-2108">Truth Equality and JavaScript</a> 了解更多</p>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-块" class="anchor" href="#%E5%9D%97" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-blocks">块</a>
</h2>

<ul class="task-list">
<li>
<p>给所有多行的块使用大括号</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">if</span> (test)
  <span class="pl-k">return</span> <span class="pl-c1">false</span>;

<span class="pl-c">// good</span>
<span class="pl-k">if</span> (test) <span class="pl-k">return</span> <span class="pl-c1">false</span>;

<span class="pl-c">// good</span>
<span class="pl-k">if</span> (test) {
  <span class="pl-k">return</span> <span class="pl-c1">false</span>;
}

<span class="pl-c">// bad</span>
<span class="pl-k">function</span>() { <span class="pl-k">return</span> <span class="pl-c1">false</span>; }

<span class="pl-c">// good</span>
<span class="pl-k">function</span>() {
  <span class="pl-k">return</span> <span class="pl-c1">false</span>;
}</pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-注释" class="anchor" href="#%E6%B3%A8%E9%87%8A" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-comments">注释</a>
</h2>

<ul class="task-list">
<li>
<p>使用 <code>/** ... */</code> 进行多行注释，包括描述，指定类型以及参数值和返回值</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-c">// make() returns a new element</span>
<span class="pl-c">// based on the passed in tag name</span>
<span class="pl-c">//</span>
<span class="pl-c">// @param &lt;String&gt; tag</span>
<span class="pl-c">// @return &lt;Element&gt; element</span>
<span class="pl-k">function</span> <span class="pl-en">make</span>(<span class="pl-smi">tag</span>) {

  <span class="pl-c">// ...stuff...</span>

  <span class="pl-k">return</span> element;
}

<span class="pl-c">// good</span>
<span class="pl-c">/**</span>
<span class="pl-c"> * make() returns a new element</span>
<span class="pl-c"> * based on the passed in tag name</span>
<span class="pl-c"> *</span>
<span class="pl-c"> * @param &lt;String&gt; tag</span>
<span class="pl-c"> * @return &lt;Element&gt; element</span>
<span class="pl-c"> */</span>
<span class="pl-k">function</span> <span class="pl-en">make</span>(<span class="pl-smi">tag</span>) {

  <span class="pl-c">// ...stuff...</span>

  <span class="pl-k">return</span> element;
}</pre></div>
</li>
<li>
<p>使用 <code>//</code> 进行单行注释，在评论对象的上面进行单行注释，注释前放一个空行.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">var</span> active <span class="pl-k">=</span> <span class="pl-c1">true</span>;  <span class="pl-c">// is current tab</span>

<span class="pl-c">// good</span>
<span class="pl-c">// is current tab</span>
<span class="pl-k">var</span> active <span class="pl-k">=</span> <span class="pl-c1">true</span>;

<span class="pl-c">// bad</span>
<span class="pl-k">function</span> <span class="pl-en">getType</span>() {
  <span class="pl-en">console</span><span class="pl-c1">.log</span>(<span class="pl-s"><span class="pl-pds">'</span>fetching type...<span class="pl-pds">'</span></span>);
  <span class="pl-c">// set the default type to 'no type'</span>
  <span class="pl-k">var</span> type <span class="pl-k">=</span> <span class="pl-v">this</span>._type <span class="pl-k">||</span> <span class="pl-s"><span class="pl-pds">'</span>no type<span class="pl-pds">'</span></span>;

  <span class="pl-k">return</span> type;
}

<span class="pl-c">// good</span>
<span class="pl-k">function</span> <span class="pl-en">getType</span>() {
  <span class="pl-en">console</span><span class="pl-c1">.log</span>(<span class="pl-s"><span class="pl-pds">'</span>fetching type...<span class="pl-pds">'</span></span>);

  <span class="pl-c">// set the default type to 'no type'</span>
  <span class="pl-k">var</span> type <span class="pl-k">=</span> <span class="pl-v">this</span>._type <span class="pl-k">||</span> <span class="pl-s"><span class="pl-pds">'</span>no type<span class="pl-pds">'</span></span>;

  <span class="pl-k">return</span> type;
}</pre></div>
</li>
<li>
<p>如果你有一个问题需要重新来看一下或如果你建议一个需要被实现的解决方法的话需要在你的注释前面加上 <code>FIXME</code> 或 <code>TODO</code> 帮助其他人迅速理解</p>

<div class="highlight highlight-javascript"><pre><span class="pl-k">function</span> <span class="pl-en">Calculator</span>() {

  <span class="pl-c">// FIXME: shouldn't use a global here</span>
  total <span class="pl-k">=</span> <span class="pl-c1">0</span>;

  <span class="pl-k">return</span> <span class="pl-v">this</span>;
}</pre></div>

<div class="highlight highlight-javascript"><pre><span class="pl-k">function</span> <span class="pl-en">Calculator</span>() {

  <span class="pl-c">// TODO: total should be configurable by an options param</span>
  <span class="pl-v">this</span>.total <span class="pl-k">=</span> <span class="pl-c1">0</span>;

  <span class="pl-k">return</span> <span class="pl-v">this</span>;
}</pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-空白" class="anchor" href="#%E7%A9%BA%E7%99%BD" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-whitespace">空白</a>
</h2>

<ul class="task-list">
<li>
<p>将tab设为4个空格</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">function</span>() {
∙∙<span class="pl-k">var</span> name;
}

<span class="pl-c">// bad</span>
<span class="pl-k">function</span>() {
∙<span class="pl-k">var</span> name;
}

<span class="pl-c">// good</span>
<span class="pl-k">function</span>() {
∙∙∙∙<span class="pl-k">var</span> name;
}</pre></div>
</li>
<li>
<p>大括号前放一个空格</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">function</span> <span class="pl-en">test</span>(){
  <span class="pl-en">console</span><span class="pl-c1">.log</span>(<span class="pl-s"><span class="pl-pds">'</span>test<span class="pl-pds">'</span></span>);
}

<span class="pl-c">// good</span>
<span class="pl-k">function</span> <span class="pl-en">test</span>() {
  <span class="pl-en">console</span><span class="pl-c1">.log</span>(<span class="pl-s"><span class="pl-pds">'</span>test<span class="pl-pds">'</span></span>);
}

<span class="pl-c">// bad</span>
dog.set(<span class="pl-s"><span class="pl-pds">'</span>attr<span class="pl-pds">'</span></span>,{
  age<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>1 year<span class="pl-pds">'</span></span>,
  breed<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>Bernese Mountain Dog<span class="pl-pds">'</span></span>
});

<span class="pl-c">// good</span>
dog.set(<span class="pl-s"><span class="pl-pds">'</span>attr<span class="pl-pds">'</span></span>, {
  age<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>1 year<span class="pl-pds">'</span></span>,
  breed<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>Bernese Mountain Dog<span class="pl-pds">'</span></span>
});</pre></div>
</li>
<li>
<p>在做长方法链时使用缩进.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
$(<span class="pl-s"><span class="pl-pds">'</span>#items<span class="pl-pds">'</span></span>).<span class="pl-c1">find</span>(<span class="pl-s"><span class="pl-pds">'</span>.selected<span class="pl-pds">'</span></span>).highlight().end().<span class="pl-c1">find</span>(<span class="pl-s"><span class="pl-pds">'</span>.open<span class="pl-pds">'</span></span>).updateCount();

<span class="pl-c">// good</span>
$(<span class="pl-s"><span class="pl-pds">'</span>#items<span class="pl-pds">'</span></span>)
  .<span class="pl-c1">find</span>(<span class="pl-s"><span class="pl-pds">'</span>.selected<span class="pl-pds">'</span></span>)
    .highlight()
    .end()
  .<span class="pl-c1">find</span>(<span class="pl-s"><span class="pl-pds">'</span>.open<span class="pl-pds">'</span></span>)
    .updateCount();

<span class="pl-c">// bad</span>
<span class="pl-k">var</span> leds <span class="pl-k">=</span> stage.selectAll(<span class="pl-s"><span class="pl-pds">'</span>.led<span class="pl-pds">'</span></span>).<span class="pl-c1">data</span>(data).enter().append(<span class="pl-s"><span class="pl-pds">'</span>svg:svg<span class="pl-pds">'</span></span>).class(<span class="pl-s"><span class="pl-pds">'</span>led<span class="pl-pds">'</span></span>, <span class="pl-c1">true</span>)
    .attr(<span class="pl-s"><span class="pl-pds">'</span>width<span class="pl-pds">'</span></span>,  (radius <span class="pl-k">+</span> margin) <span class="pl-k">*</span> <span class="pl-c1">2</span>).append(<span class="pl-s"><span class="pl-pds">'</span>svg:g<span class="pl-pds">'</span></span>)
    .attr(<span class="pl-s"><span class="pl-pds">'</span>transform<span class="pl-pds">'</span></span>, <span class="pl-s"><span class="pl-pds">'</span>translate(<span class="pl-pds">'</span></span> <span class="pl-k">+</span> (radius <span class="pl-k">+</span> margin) <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span>,<span class="pl-pds">'</span></span> <span class="pl-k">+</span> (radius <span class="pl-k">+</span> margin) <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span>)<span class="pl-pds">'</span></span>)
    .<span class="pl-c1">call</span>(tron.led);

<span class="pl-c">// good</span>
<span class="pl-k">var</span> leds <span class="pl-k">=</span> stage.selectAll(<span class="pl-s"><span class="pl-pds">'</span>.led<span class="pl-pds">'</span></span>)
    .<span class="pl-c1">data</span>(data)
  .enter().append(<span class="pl-s"><span class="pl-pds">'</span>svg:svg<span class="pl-pds">'</span></span>)
    .class(<span class="pl-s"><span class="pl-pds">'</span>led<span class="pl-pds">'</span></span>, <span class="pl-c1">true</span>)
    .attr(<span class="pl-s"><span class="pl-pds">'</span>width<span class="pl-pds">'</span></span>,  (radius <span class="pl-k">+</span> margin) <span class="pl-k">*</span> <span class="pl-c1">2</span>)
  .append(<span class="pl-s"><span class="pl-pds">'</span>svg:g<span class="pl-pds">'</span></span>)
    .attr(<span class="pl-s"><span class="pl-pds">'</span>transform<span class="pl-pds">'</span></span>, <span class="pl-s"><span class="pl-pds">'</span>translate(<span class="pl-pds">'</span></span> <span class="pl-k">+</span> (radius <span class="pl-k">+</span> margin) <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span>,<span class="pl-pds">'</span></span> <span class="pl-k">+</span> (radius <span class="pl-k">+</span> margin) <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span>)<span class="pl-pds">'</span></span>)
    .<span class="pl-c1">call</span>(tron.led);</pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-逗号" class="anchor" href="#%E9%80%97%E5%8F%B7" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-commas">逗号</a>
</h2>

<ul class="task-list">
<li>
<p>不要将逗号放前面</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">var</span> once
  , upon
  , aTime;

<span class="pl-c">// good</span>
<span class="pl-k">var</span> once,
    upon,
    aTime;

<span class="pl-c">// bad</span>
<span class="pl-k">var</span> hero <span class="pl-k">=</span> {
    firstName<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>Bob<span class="pl-pds">'</span></span>
  , lastName<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>Parr<span class="pl-pds">'</span></span>
  , heroName<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>Mr. Incredible<span class="pl-pds">'</span></span>
  , superPower<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>strength<span class="pl-pds">'</span></span>
};

<span class="pl-c">// good</span>
<span class="pl-k">var</span> hero <span class="pl-k">=</span> {
  firstName<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>Bob<span class="pl-pds">'</span></span>,
  lastName<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>Parr<span class="pl-pds">'</span></span>,
  heroName<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>Mr. Incredible<span class="pl-pds">'</span></span>,
  superPower<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>strength<span class="pl-pds">'</span></span>
};</pre></div>
</li>
<li>
<p>不要加多余的逗号，这可能会在IE下引起错误，同时如果多一个逗号某些ES3的实现会计算多数组的长度。</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">var</span> hero <span class="pl-k">=</span> {
  firstName<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>Kevin<span class="pl-pds">'</span></span>,
  lastName<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>Flynn<span class="pl-pds">'</span></span>,
};

<span class="pl-k">var</span> heroes <span class="pl-k">=</span> [
  <span class="pl-s"><span class="pl-pds">'</span>Batman<span class="pl-pds">'</span></span>,
  <span class="pl-s"><span class="pl-pds">'</span>Superman<span class="pl-pds">'</span></span>,
];

<span class="pl-c">// good</span>
<span class="pl-k">var</span> hero <span class="pl-k">=</span> {
  firstName<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>Kevin<span class="pl-pds">'</span></span>,
  lastName<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>Flynn<span class="pl-pds">'</span></span>
};

<span class="pl-k">var</span> heroes <span class="pl-k">=</span> [
  <span class="pl-s"><span class="pl-pds">'</span>Batman<span class="pl-pds">'</span></span>,
  <span class="pl-s"><span class="pl-pds">'</span>Superman<span class="pl-pds">'</span></span>
];</pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-分号" class="anchor" href="#%E5%88%86%E5%8F%B7" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-semicolons">分号</a>
</h2>

<ul class="task-list">
<li>
<p>语句结束一定要加分号</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
(<span class="pl-k">function</span>() {
  <span class="pl-k">var</span> name <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>Skywalker<span class="pl-pds">'</span></span>
  <span class="pl-k">return</span> name
})()

<span class="pl-c">// good</span>
(<span class="pl-k">function</span>() {
  <span class="pl-k">var</span> name <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>Skywalker<span class="pl-pds">'</span></span>;
  <span class="pl-k">return</span> name;
})();

<span class="pl-c">// good</span>
;(<span class="pl-k">function</span>() {
  <span class="pl-k">var</span> name <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>Skywalker<span class="pl-pds">'</span></span>;
  <span class="pl-k">return</span> name;
})();</pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-类型转换" class="anchor" href="#%E7%B1%BB%E5%9E%8B%E8%BD%AC%E6%8D%A2" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-type-coercion">类型转换</a>
</h2>

<ul class="task-list">
<li>在语句的开始执行类型转换.</li>
<li>
<p>字符串:</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">//  =&gt; this.reviewScore = 9;</span>

<span class="pl-c">// bad</span>
<span class="pl-k">var</span> totalScore <span class="pl-k">=</span> <span class="pl-v">this</span>.reviewScore <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span><span class="pl-pds">'</span></span>;

<span class="pl-c">// good</span>
<span class="pl-k">var</span> totalScore <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span><span class="pl-pds">'</span></span> <span class="pl-k">+</span> <span class="pl-v">this</span>.reviewScore;

<span class="pl-c">// bad</span>
<span class="pl-k">var</span> totalScore <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span><span class="pl-pds">'</span></span> <span class="pl-k">+</span> <span class="pl-v">this</span>.reviewScore <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span> total score<span class="pl-pds">'</span></span>;

<span class="pl-c">// good</span>
<span class="pl-k">var</span> totalScore <span class="pl-k">=</span> <span class="pl-v">this</span>.reviewScore <span class="pl-k">+</span> <span class="pl-s"><span class="pl-pds">'</span> total score<span class="pl-pds">'</span></span>;</pre></div>
</li>
<li>
<p>对数字使用 <code>parseInt</code> 并且总是带上类型转换的基数.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-k">var</span> inputValue <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>4<span class="pl-pds">'</span></span>;

<span class="pl-c">// bad</span>
<span class="pl-k">var</span> val <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">Number</span>(inputValue);

<span class="pl-c">// bad</span>
<span class="pl-k">var</span> val <span class="pl-k">=</span> <span class="pl-k">+</span>inputValue;

<span class="pl-c">// bad</span>
<span class="pl-k">var</span> val <span class="pl-k">=</span> inputValue <span class="pl-k">&gt;&gt;</span> <span class="pl-c1">0</span>;

<span class="pl-c">// bad</span>
<span class="pl-k">var</span> val <span class="pl-k">=</span> <span class="pl-c1">parseInt</span>(inputValue);

<span class="pl-c">// good</span>
<span class="pl-k">var</span> val <span class="pl-k">=</span> <span class="pl-c1">Number</span>(inputValue);

<span class="pl-c">// good</span>
<span class="pl-k">var</span> val <span class="pl-k">=</span> <span class="pl-c1">parseInt</span>(inputValue, <span class="pl-c1">10</span>);

<span class="pl-c">// good</span>
<span class="pl-c">/**</span>
<span class="pl-c"> * parseInt was the reason my code was slow.</span>
<span class="pl-c"> * Bitshifting the String to coerce it to a</span>
<span class="pl-c"> * Number made it a lot faster.</span>
<span class="pl-c"> */</span>
<span class="pl-k">var</span> val <span class="pl-k">=</span> inputValue <span class="pl-k">&gt;&gt;</span> <span class="pl-c1">0</span>;</pre></div>
</li>
<li>
<p>布尔值:</p>

<div class="highlight highlight-javascript"><pre><span class="pl-k">var</span> age <span class="pl-k">=</span> <span class="pl-c1">0</span>;

<span class="pl-c">// bad</span>
<span class="pl-k">var</span> hasAge <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">Boolean</span>(age);

<span class="pl-c">// good</span>
<span class="pl-k">var</span> hasAge <span class="pl-k">=</span> <span class="pl-c1">Boolean</span>(age);

<span class="pl-c">// good</span>
<span class="pl-k">var</span> hasAge <span class="pl-k">=</span> <span class="pl-k">!!</span>age;</pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-命名约定" class="anchor" href="#%E5%91%BD%E5%90%8D%E7%BA%A6%E5%AE%9A" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-naming-conventions">命名约定</a>
</h2>

<ul class="task-list">
<li>
<p>避免单个字符名，让你的变量名有描述意义。</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">function</span> <span class="pl-en">q</span>() {
  <span class="pl-c">// ...stuff...</span>
}

<span class="pl-c">// good</span>
<span class="pl-k">function</span> <span class="pl-en">query</span>() {
  <span class="pl-c">// ..stuff..</span>
}</pre></div>
</li>
<li>
<p>当命名对象、函数和实例时使用驼峰命名规则</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">var</span> OBJEcttsssss <span class="pl-k">=</span> {};
<span class="pl-k">var</span> this_is_my_object <span class="pl-k">=</span> {};
<span class="pl-k">var</span> <span class="pl-v">this</span><span class="pl-k">-</span>is<span class="pl-k">-</span>my<span class="pl-k">-</span>object <span class="pl-k">=</span> {};
<span class="pl-k">function</span> <span class="pl-en">c</span>() {};
<span class="pl-k">var</span> u <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">user</span>({
  name<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>Bob Parr<span class="pl-pds">'</span></span>
});

<span class="pl-c">// good</span>
<span class="pl-k">var</span> thisIsMyObject <span class="pl-k">=</span> {};
<span class="pl-k">function</span> <span class="pl-en">thisIsMyFunction</span>() {};
<span class="pl-k">var</span> user <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">User</span>({
  name<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>Bob Parr<span class="pl-pds">'</span></span>
});</pre></div>
</li>
<li>
<p>当命名构造函数或类时使用驼峰式大写</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">function</span> <span class="pl-en">user</span>(<span class="pl-smi">options</span>) {
  <span class="pl-v">this</span>.<span class="pl-c1">name</span> <span class="pl-k">=</span> options.<span class="pl-c1">name</span>;
}

<span class="pl-k">var</span> bad <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">user</span>({
  name<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>nope<span class="pl-pds">'</span></span>
});

<span class="pl-c">// good</span>
<span class="pl-k">function</span> <span class="pl-en">User</span>(<span class="pl-smi">options</span>) {
  <span class="pl-v">this</span>.<span class="pl-c1">name</span> <span class="pl-k">=</span> options.<span class="pl-c1">name</span>;
}

<span class="pl-k">var</span> good <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">User</span>({
  name<span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>yup<span class="pl-pds">'</span></span>
});</pre></div>
</li>
<li>
<p>命名私有属性时前面加个下划线 <code>_</code></p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-v">this</span>.__firstName__ <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>Panda<span class="pl-pds">'</span></span>;
<span class="pl-v">this</span>.firstName_ <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>Panda<span class="pl-pds">'</span></span>;

<span class="pl-c">// good</span>
<span class="pl-v">this</span>._firstName <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">'</span>Panda<span class="pl-pds">'</span></span>;</pre></div>
</li>
<li>
<p>当保存对 <code>this</code> 的引用时使用 <code>_this</code>.</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">function</span>() {
  <span class="pl-k">var</span> self <span class="pl-k">=</span> <span class="pl-v">this</span>;
  <span class="pl-k">return</span> <span class="pl-k">function</span>() {
    <span class="pl-en">console</span><span class="pl-c1">.log</span>(self);
  };
}

<span class="pl-c">// bad</span>
<span class="pl-k">function</span>() {
  <span class="pl-k">var</span> that <span class="pl-k">=</span> <span class="pl-v">this</span>;
  <span class="pl-k">return</span> <span class="pl-k">function</span>() {
    <span class="pl-en">console</span><span class="pl-c1">.log</span>(that);
  };
}

<span class="pl-c">// good</span>
<span class="pl-k">function</span>() {
  <span class="pl-k">var</span> _this <span class="pl-k">=</span> <span class="pl-v">this</span>;
  <span class="pl-k">return</span> <span class="pl-k">function</span>() {
    <span class="pl-en">console</span><span class="pl-c1">.log</span>(_this);
  };
}</pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-存取器" class="anchor" href="#%E5%AD%98%E5%8F%96%E5%99%A8" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-accessors">存取器</a>
</h2>

<ul class="task-list">
<li>属性的存取器函数不是必需的</li>
<li>
<p>如果你确实有存取器函数的话使用getVal() 和 setVal('hello')</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
dragon.age();

<span class="pl-c">// good</span>
dragon.getAge();

<span class="pl-c">// bad</span>
dragon.age(<span class="pl-c1">25</span>);

<span class="pl-c">// good</span>
dragon.setAge(<span class="pl-c1">25</span>);</pre></div>
</li>
<li>
<p>如果属性是布尔值，使用isVal() 或 hasVal()</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">if</span> (<span class="pl-k">!</span>dragon.age()) {
  <span class="pl-k">return</span> <span class="pl-c1">false</span>;
}

<span class="pl-c">// good</span>
<span class="pl-k">if</span> (<span class="pl-k">!</span>dragon.hasAge()) {
  <span class="pl-k">return</span> <span class="pl-c1">false</span>;
}</pre></div>
</li>
<li>
<p>可以创建get()和set()函数，但是要保持一致</p>

<div class="highlight highlight-javascript"><pre><span class="pl-k">function</span> <span class="pl-en">Jedi</span>(<span class="pl-smi">options</span>) {
  options <span class="pl-k">||</span> (options <span class="pl-k">=</span> {});
  <span class="pl-k">var</span> lightsaber <span class="pl-k">=</span> options.lightsaber <span class="pl-k">||</span> <span class="pl-s"><span class="pl-pds">'</span>blue<span class="pl-pds">'</span></span>;
  <span class="pl-v">this</span>.set(<span class="pl-s"><span class="pl-pds">'</span>lightsaber<span class="pl-pds">'</span></span>, lightsaber);
}

<span class="pl-c1">Jedi</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">set</span> <span class="pl-k">=</span> <span class="pl-k">function</span>(<span class="pl-smi">key</span>, <span class="pl-smi">val</span>) {
  <span class="pl-v">this</span>[key] <span class="pl-k">=</span> val;
};

<span class="pl-c1">Jedi</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">get</span> <span class="pl-k">=</span> <span class="pl-k">function</span>(<span class="pl-smi">key</span>) {
  <span class="pl-k">return</span> <span class="pl-v">this</span>[key];
};</pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-构造器" class="anchor" href="#%E6%9E%84%E9%80%A0%E5%99%A8" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-constructors">构造器</a>
</h2>

<ul class="task-list">
<li>
<p>给对象原型分配方法，而不是用一个新的对象覆盖原型，覆盖原型会使继承出现问题。</p>

<div class="highlight highlight-javascript"><pre><span class="pl-k">function</span> <span class="pl-en">Jedi</span>() {
  <span class="pl-en">console</span><span class="pl-c1">.log</span>(<span class="pl-s"><span class="pl-pds">'</span>new jedi<span class="pl-pds">'</span></span>);
}

<span class="pl-c">// bad</span>
<span class="pl-c1">Jedi</span>.<span class="pl-c1">prototype</span> <span class="pl-k">=</span> {
  <span class="pl-en">fight</span>: <span class="pl-k">function</span> <span class="pl-en">fight</span>() {
    <span class="pl-en">console</span><span class="pl-c1">.log</span>(<span class="pl-s"><span class="pl-pds">'</span>fighting<span class="pl-pds">'</span></span>);
  },

  <span class="pl-en">block</span>: <span class="pl-k">function</span> <span class="pl-en">block</span>() {
    <span class="pl-en">console</span><span class="pl-c1">.log</span>(<span class="pl-s"><span class="pl-pds">'</span>blocking<span class="pl-pds">'</span></span>);
  }
};

<span class="pl-c">// good</span>
<span class="pl-c1">Jedi</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">fight</span> <span class="pl-k">=</span> <span class="pl-k">function</span> <span class="pl-en">fight</span>() {
  <span class="pl-en">console</span><span class="pl-c1">.log</span>(<span class="pl-s"><span class="pl-pds">'</span>fighting<span class="pl-pds">'</span></span>);
};

<span class="pl-c1">Jedi</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">block</span> <span class="pl-k">=</span> <span class="pl-k">function</span> <span class="pl-en">block</span>() {
  <span class="pl-en">console</span><span class="pl-c1">.log</span>(<span class="pl-s"><span class="pl-pds">'</span>blocking<span class="pl-pds">'</span></span>);
};</pre></div>
</li>
<li>
<p>方法可以返回 <code>this</code> 帮助方法可链。</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-c1">Jedi</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">jump</span> <span class="pl-k">=</span> <span class="pl-k">function</span>() {
  <span class="pl-v">this</span>.jumping <span class="pl-k">=</span> <span class="pl-c1">true</span>;
  <span class="pl-k">return</span> <span class="pl-c1">true</span>;
};

<span class="pl-c1">Jedi</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">setHeight</span> <span class="pl-k">=</span> <span class="pl-k">function</span>(<span class="pl-smi">height</span>) {
  <span class="pl-v">this</span>.<span class="pl-c1">height</span> <span class="pl-k">=</span> height;
};

<span class="pl-k">var</span> luke <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">Jedi</span>();
luke.jump(); <span class="pl-c">// =&gt; true</span>
luke.setHeight(<span class="pl-c1">20</span>) <span class="pl-c">// =&gt; undefined</span>

<span class="pl-c">// good</span>
<span class="pl-c1">Jedi</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">jump</span> <span class="pl-k">=</span> <span class="pl-k">function</span>() {
  <span class="pl-v">this</span>.jumping <span class="pl-k">=</span> <span class="pl-c1">true</span>;
  <span class="pl-k">return</span> <span class="pl-v">this</span>;
};

<span class="pl-c1">Jedi</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">setHeight</span> <span class="pl-k">=</span> <span class="pl-k">function</span>(<span class="pl-smi">height</span>) {
  <span class="pl-v">this</span>.<span class="pl-c1">height</span> <span class="pl-k">=</span> height;
  <span class="pl-k">return</span> <span class="pl-v">this</span>;
};

<span class="pl-k">var</span> luke <span class="pl-k">=</span> <span class="pl-k">new</span> <span class="pl-en">Jedi</span>();

luke.jump()
  .setHeight(<span class="pl-c1">20</span>);</pre></div>
</li>
<li>
<p>可以写一个自定义的toString()方法，但是确保它工作正常并且不会有副作用。</p>

<div class="highlight highlight-javascript"><pre><span class="pl-k">function</span> <span class="pl-en">Jedi</span>(<span class="pl-smi">options</span>) {
  options <span class="pl-k">||</span> (options <span class="pl-k">=</span> {});
  <span class="pl-v">this</span>.<span class="pl-c1">name</span> <span class="pl-k">=</span> options.<span class="pl-c1">name</span> <span class="pl-k">||</span> <span class="pl-s"><span class="pl-pds">'</span>no name<span class="pl-pds">'</span></span>;
}

<span class="pl-c1">Jedi</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">getName</span> <span class="pl-k">=</span> <span class="pl-k">function</span> <span class="pl-en">getName</span>() {
  <span class="pl-k">return</span> <span class="pl-v">this</span>.<span class="pl-c1">name</span>;
};

<span class="pl-c1">Jedi</span>.<span class="pl-c1">prototype</span>.<span class="pl-en">toString</span> <span class="pl-k">=</span> <span class="pl-k">function</span> <span class="pl-en">toString</span>() {
  <span class="pl-k">return</span> <span class="pl-s"><span class="pl-pds">'</span>Jedi - <span class="pl-pds">'</span></span> <span class="pl-k">+</span> <span class="pl-v">this</span>.getName();
};</pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-事件" class="anchor" href="#%E4%BA%8B%E4%BB%B6" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-events">事件</a>
</h2>

<ul class="task-list">
<li>
<p>当给事件附加数据时，传入一个哈希而不是原始值，这可以让后面的贡献者加入更多数据到事件数据里而不用找出并更新那个事件的事件处理器</p>

<div class="highlight highlight-js"><pre><span class="pl-c">// bad</span>
$(<span class="pl-v">this</span>).trigger(<span class="pl-s"><span class="pl-pds">'</span>listingUpdated<span class="pl-pds">'</span></span>, listing.<span class="pl-c1">id</span>);

...

$(<span class="pl-v">this</span>).on(<span class="pl-s"><span class="pl-pds">'</span>listingUpdated<span class="pl-pds">'</span></span>, <span class="pl-k">function</span>(<span class="pl-smi">e</span>, <span class="pl-smi">listingId</span>) {
  <span class="pl-c">// do something with listingId</span>
});</pre></div>

<p>更好:</p>

<div class="highlight highlight-js"><pre><span class="pl-c">// good</span>
$(<span class="pl-v">this</span>).trigger(<span class="pl-s"><span class="pl-pds">'</span>listingUpdated<span class="pl-pds">'</span></span>, { listingId <span class="pl-k">:</span> listing.<span class="pl-c1">id</span> });

...

$(<span class="pl-v">this</span>).on(<span class="pl-s"><span class="pl-pds">'</span>listingUpdated<span class="pl-pds">'</span></span>, <span class="pl-k">function</span>(<span class="pl-smi">e</span>, <span class="pl-smi">data</span>) {
  <span class="pl-c">// do something with data.listingId</span>
});</pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-模块" class="anchor" href="#%E6%A8%A1%E5%9D%97" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-modules">模块</a>
</h2>

<ul class="task-list">
<li>模块应该以 <code>!</code> 开始，这保证了如果一个有问题的模块忘记包含最后的分号在合并后不会出现错误</li>
<li>这个文件应该以驼峰命名，并在同名文件夹下，同时导出的时候名字一致</li>
<li>加入一个名为noConflict()的方法来设置导出的模块为之前的版本并返回它</li>
<li>
<p>总是在模块顶部声明 <code>'use strict';</code></p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// fancyInput/fancyInput.js</span>

<span class="pl-k">!</span><span class="pl-k">function</span>(<span class="pl-smi">global</span>) {
  <span class="pl-s"><span class="pl-pds">'</span>use strict<span class="pl-pds">'</span></span>;

  <span class="pl-k">var</span> previousFancyInput <span class="pl-k">=</span> <span class="pl-c1">global</span>.FancyInput;

  <span class="pl-k">function</span> <span class="pl-en">FancyInput</span>(<span class="pl-smi">options</span>) {
    <span class="pl-v">this</span>.<span class="pl-c1">options</span> <span class="pl-k">=</span> options <span class="pl-k">||</span> {};
  }

  <span class="pl-c1">FancyInput</span>.<span class="pl-en">noConflict</span> <span class="pl-k">=</span> <span class="pl-k">function</span> <span class="pl-en">noConflict</span>() {
    <span class="pl-c1">global</span>.FancyInput <span class="pl-k">=</span> previousFancyInput;
    <span class="pl-k">return</span> FancyInput;
  };

  <span class="pl-c1">global</span>.FancyInput <span class="pl-k">=</span> FancyInput;
}(<span class="pl-v">this</span>);</pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-jquery" class="anchor" href="#jquery" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-jquery">jQuery</a>
</h2>

<ul class="task-list">
<li>
<p>缓存jQuery查询</p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
<span class="pl-k">function</span> <span class="pl-en">setSidebar</span>() {
  $(<span class="pl-s"><span class="pl-pds">'</span>.sidebar<span class="pl-pds">'</span></span>).hide();

  <span class="pl-c">// ...stuff...</span>

  $(<span class="pl-s"><span class="pl-pds">'</span>.sidebar<span class="pl-pds">'</span></span>).css({
    <span class="pl-s"><span class="pl-pds">'</span>background-color<span class="pl-pds">'</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>pink<span class="pl-pds">'</span></span>
  });
}

<span class="pl-c">// good</span>
<span class="pl-k">function</span> <span class="pl-en">setSidebar</span>() {
  <span class="pl-k">var</span> $sidebar <span class="pl-k">=</span> $(<span class="pl-s"><span class="pl-pds">'</span>.sidebar<span class="pl-pds">'</span></span>);
  $sidebar.hide();

  <span class="pl-c">// ...stuff...</span>

  $sidebar.css({
    <span class="pl-s"><span class="pl-pds">'</span>background-color<span class="pl-pds">'</span></span><span class="pl-k">:</span> <span class="pl-s"><span class="pl-pds">'</span>pink<span class="pl-pds">'</span></span>
  });
}</pre></div>
</li>
<li><p>对DOM查询使用级联的 <code>$('.sidebar ul')</code> 或 <code>$('.sidebar ul')</code>，<a href="http://jsperf.com/jquery-find-vs-context-sel/16">jsPerf</a></p></li>
<li>
<p>对有作用域的jQuery对象查询使用 <code>find</code></p>

<div class="highlight highlight-javascript"><pre><span class="pl-c">// bad</span>
$(<span class="pl-s"><span class="pl-pds">'</span>.sidebar<span class="pl-pds">'</span></span>, <span class="pl-s"><span class="pl-pds">'</span>ul<span class="pl-pds">'</span></span>).hide();

<span class="pl-c">// bad</span>
$(<span class="pl-s"><span class="pl-pds">'</span>.sidebar<span class="pl-pds">'</span></span>).<span class="pl-c1">find</span>(<span class="pl-s"><span class="pl-pds">'</span>ul<span class="pl-pds">'</span></span>).hide();

<span class="pl-c">// good</span>
$(<span class="pl-s"><span class="pl-pds">'</span>.sidebar ul<span class="pl-pds">'</span></span>).hide();

<span class="pl-c">// good</span>
$(<span class="pl-s"><span class="pl-pds">'</span>.sidebar &gt; ul<span class="pl-pds">'</span></span>).hide();

<span class="pl-c">// good (slower)</span>
$sidebar.<span class="pl-c1">find</span>(<span class="pl-s"><span class="pl-pds">'</span>ul<span class="pl-pds">'</span></span>);

<span class="pl-c">// good (faster)</span>
$($sidebar[<span class="pl-c1">0</span>]).<span class="pl-c1">find</span>(<span class="pl-s"><span class="pl-pds">'</span>ul<span class="pl-pds">'</span></span>);</pre></div>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-ecmascript-5兼容性" class="anchor" href="#ecmascript-5%E5%85%BC%E5%AE%B9%E6%80%A7" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-es5">ECMAScript 5兼容性</a>
</h2>

<ul class="task-list">
<li>
<p>参考<a href="https://twitter.com/kangax/">Kangax</a>的 ES5 <a href="http://kangax.github.com/es5-compat-table/">compatibility table</a></p>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-性能" class="anchor" href="#%E6%80%A7%E8%83%BD" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-performance">性能</a>
</h2>

<ul class="task-list">
<li><a href="http://kellegous.com/j/2013/01/26/layout-performance/">On Layout &amp; Web Performance</a></li>
<li><a href="http://jsperf.com/string-vs-array-concat/2">String vs Array Concat</a></li>
<li><a href="http://jsperf.com/try-catch-in-loop-cost">Try/Catch Cost In a Loop</a></li>
<li><a href="http://jsperf.com/bang-function">Bang Function</a></li>
<li><a href="http://jsperf.com/jquery-find-vs-context-sel/13">jQuery Find vs Context, Selector</a></li>
<li><a href="http://jsperf.com/innerhtml-vs-textcontent-for-script-text">innerHTML vs textContent for script text</a></li>
<li><a href="http://jsperf.com/ya-string-concat">Long String Concatenation</a></li>
<li>
<p>Loading...</p>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-资源" class="anchor" href="#%E8%B5%84%E6%BA%90" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-resources">资源</a>
</h2>

<p><strong>Read This</strong></p>

<ul class="task-list">
<li><a href="http://es5.github.com/">Annotated ECMAScript 5.1</a></li>
</ul>

<p><strong>其它规范</strong></p>

<ul class="task-list">
<li><a href="http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml">Google JavaScript Style Guide</a></li>
<li><a href="http://docs.jquery.com/JQuery_Core_Style_Guidelines">jQuery Core Style Guidelines</a></li>
<li><a href="https://github.com/rwldrn/idiomatic.js/">Principles of Writing Consistent, Idiomatic JavaScript</a></li>
</ul>

<p><strong>其它风格</strong></p>

<ul class="task-list">
<li>
<a href="https://gist.github.com/4135065">Naming this in nested functions</a> - Christian Johansen</li>
<li><a href="https://github.com/airbnb/javascript/issues/52">Conditional Callbacks</a></li>
</ul>

<p><strong>阅读更多</strong></p>

<ul class="task-list">
<li>
<a href="http://javascriptweblog.wordpress.com/2010/10/25/understanding-javascript-closures/">Understanding JavaScript Closures</a> - Angus Croll</li>
</ul>

<p><strong>书籍</strong></p>

<ul class="task-list">
<li>
<a href="http://www.amazon.com/JavaScript-Good-Parts-Douglas-Crockford/dp/0596517742">JavaScript: The Good Parts</a> - Douglas Crockford</li>
<li>
<a href="http://www.amazon.com/JavaScript-Patterns-Stoyan-Stefanov/dp/0596806752">JavaScript Patterns</a> - Stoyan Stefanov</li>
<li>
<a href="http://www.amazon.com/JavaScript-Design-Patterns-Recipes-Problem-Solution/dp/159059908X">Pro JavaScript Design Patterns</a>  - Ross Harmes and Dustin Diaz</li>
<li>
<a href="http://www.amazon.com/High-Performance-Web-Sites-Essential/dp/0596529309">High Performance Web Sites: Essential Knowledge for Front-End Engineers</a> - Steve Souders</li>
<li>
<a href="http://www.amazon.com/Maintainable-JavaScript-Nicholas-C-Zakas/dp/1449327680">Maintainable JavaScript</a> - Nicholas C. Zakas</li>
<li>
<a href="http://www.amazon.com/JavaScript-Web-Applications-Alex-MacCaw/dp/144930351X">JavaScript Web Applications</a> - Alex MacCaw</li>
<li>
<a href="http://www.amazon.com/Pro-JavaScript-Techniques-John-Resig/dp/1590597273">Pro JavaScript Techniques</a> - John Resig</li>
<li>
<a href="http://www.amazon.com/Smashing-Node-js-JavaScript-Everywhere-Magazine/dp/1119962595">Smashing Node.js: JavaScript Everywhere</a> - Guillermo Rauch</li>
</ul>

<p><strong>博客</strong></p>

<ul class="task-list">
<li><a href="http://adamlu.com/">Adam Lu</a></li>
<li><a href="http://dailyjs.com/">DailyJS</a></li>
<li><a href="http://javascriptweekly.com/">JavaScript Weekly</a></li>
<li><a href="http://javascriptweblog.wordpress.com/">JavaScript, JavaScript...</a></li>
<li><a href="http://weblog.bocoup.com/">Bocoup Weblog</a></li>
<li><a href="http://www.adequatelygood.com/">Adequately Good</a></li>
<li><a href="http://www.nczonline.net/">NCZOnline</a></li>
<li><a href="http://perfectionkills.com/">Perfection Kills</a></li>
<li><a href="http://benalman.com/">Ben Alman</a></li>
<li><a href="http://dmitry.baranovskiy.com/">Dmitry Baranovskiy</a></li>
<li><a href="http://dustindiaz.com/">Dustin Diaz</a></li>
<li>
<p><a href="http://net.tutsplus.com/?s=javascript">nettuts</a></p>

<p><strong><a href="#TOC">[⬆]</a></strong></p>
</li>
</ul>

<h2>
<a id="user-content-哪些人在使用" class="anchor" href="#%E5%93%AA%E4%BA%9B%E4%BA%BA%E5%9C%A8%E4%BD%BF%E7%94%A8" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-in-the-wild">哪些人在使用</a>
</h2>

<p>这是一些使用这个风格规范的组织，给我们发pull request或打开一个问题，我们会把你加到列表中。</p>

<ul class="task-list">
<li>
<strong>Airbnb</strong>: <a href="https://github.com/airbnb/javascript">airbnb/javascript</a>
</li>
<li>
<strong>American Insitutes for Research</strong>: <a href="https://github.com/AIRAST/javascript">AIRAST/javascript</a>
</li>
<li>
<strong>ExactTarget</strong>: <a href="https://github.com/ExactTarget/javascript">ExactTarget/javascript</a>
</li>
<li>
<strong>GeneralElectric</strong>: <a href="https://github.com/GeneralElectric/javascript">GeneralElectric/javascript</a>
</li>
<li>
<strong>GoodData</strong>: <a href="https://github.com/gooddata/gdc-js-style">gooddata/gdc-js-style</a>
</li>
<li>
<strong>How About We</strong>: <a href="https://github.com/howaboutwe/javascript">howaboutwe/javascript</a>
</li>
<li>
<strong>MinnPost</strong>: <a href="https://github.com/MinnPost/javascript">MinnPost/javascript</a>
</li>
<li>
<strong>ModCloth</strong>: <a href="https://github.com/modcloth/javascript">modcloth/javascript</a>
</li>
<li>
<strong>National Geographic</strong>: <a href="https://github.com/natgeo/javascript">natgeo/javascript</a>
</li>
<li>
<strong>National Park Service</strong>: <a href="https://github.com/nationalparkservice/javascript">nationalparkservice/javascript</a>
</li>
<li>
<strong>Razorfish</strong>: <a href="https://github.com/razorfish/javascript-style-guide">razorfish/javascript-style-guide</a>
</li>
<li>
<strong>Shutterfly</strong>: <a href="https://github.com/shutterfly/javascript">shutterfly/javascript</a>
</li>
<li>
<strong>Userify</strong>: <a href="https://github.com/userify/javascript">userify/javascript</a>
</li>
<li>
<strong>Zillow</strong>: <a href="https://github.com/zillow/javascript">zillow/javascript</a>
</li>
<li>
<strong>ZocDoc</strong>: <a href="https://github.com/ZocDoc/javascript">ZocDoc/javascript</a>
</li>
</ul>

<h2>
<a id="user-content-翻译" class="anchor" href="#%E7%BF%BB%E8%AF%91" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-translation">翻译</a>
</h2>

<p>这个风格规范也有其它语言版本：</p>

<ul class="task-list">
<li>:de: <strong>German</strong>: <a href="https://github.com/timofurrer/javascript-style-guide">timofurrer/javascript-style-guide</a>
</li>
<li>:jp: <strong>Japanese</strong>: <a href="https://github.com/mitsuruog/javacript-style-guide">mitsuruog/javacript-style-guide</a>
</li>
<li>:br: <strong>Portuguese</strong>: <a href="https://github.com/armoucar/javascript-style-guide">armoucar/javascript-style-guide</a>
</li>
<li>:cn: <strong>Chinese</strong>: <a href="https://github.com/adamlu/javascript-style-guide">adamlu/javascript-style-guide</a>
</li>
</ul>

<h2>
<a id="user-content-javascript风格指南" class="anchor" href="#javascript%E9%A3%8E%E6%A0%BC%E6%8C%87%E5%8D%97" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-guide-guide">JavaScript风格指南</a>
</h2>

<ul class="task-list">
<li><a href="https://github.com/airbnb/javascript/wiki/The-JavaScript-Style-Guide-Guide">Reference</a></li>
</ul>

<h2>
<a id="user-content-贡献者" class="anchor" href="#%E8%B4%A1%E7%8C%AE%E8%80%85" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-authors">贡献者</a>
</h2>

<ul class="task-list">
<li><a href="https://github.com/airbnb/javascript/graphs/contributors">View Contributors</a></li>
</ul>

<h2>
<a id="user-content-许可" class="anchor" href="#%E8%AE%B8%E5%8F%AF" aria-hidden="true"><span class="octicon octicon-link"></span></a><a name="user-content-license">许可</a>
</h2>

<p>(The MIT License)</p>

<p>Copyright (c) 2012 Airbnb</p>

<p>Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:</p>

<p>The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.</p>

<p>THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.</p>

<p><strong><a href="#TOC">[⬆]</a></strong></p>

<h1>
<a id="user-content-" class="anchor" href="#" aria-hidden="true"><span class="octicon octicon-link"></span></a>};</h1>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

        </div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.05415s from github-fe141-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
    </ul>
  </div>
</div>


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents" placeholder=""></textarea>
      <div class="suggester-container">
        <div class="suggester fullscreen-suggester js-suggester js-navigation-container"></div>
      </div>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped tooltipped-w" aria-label="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped tooltipped-w"
      aria-label="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    
    

    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-x flash-close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-2c8ae50712a47d2b83d740cb875d55cdbbb3fdbccf303951cc6b7e63731e0c38.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github-8aff85e9cebe4485d56ccdb7ec1cddc29ae18de6dac4211b8d037d21b01d8642.js"></script>
      
      

  </body>
</html>

