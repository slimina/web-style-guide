


<!DOCTYPE html>
<html lang="en" class="">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>javascript-style-guide/CSS Style Guide.md at master · adamlu/javascript-style-guide</title>
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
    <link rel="web-socket" href="wss://live.github.com/_sockets/MTEyNDA0Mzc6MDk5ZGZjOGI4MGEyNzgxOWJlZDBiZDIyOTUyYWNmZDI6NWFhNjI0MWZiOWM1ZDNkMWEwYmExMDFiZjU3OWUzYTdiNjlkYjVkOTkzYWY5NjhkODFjYzAwNjQxZmFkNjc2OQ==--ca269711a99591bec000412b1b730a83b7fdc9f9">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>
      <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="AF19BD2F:5905:16897A1:5528BE7E" name="octolytics-dimension-request_id" /><meta content="11240437" name="octolytics-actor-id" /><meta content="slimina" name="octolytics-actor-login" /><meta content="084a50266c429ca0b0aef9504c25c5cb8ec8462ac0ab00305a6ca3137c5fecb1" name="octolytics-actor-hash" />
    
    <meta content="Rails, view, blob#show" name="analytics-event" />
    <meta class="js-ga-set" name="dimension1" content="Logged In">
    <meta class="js-ga-set" name="dimension2" content="Header v3">
    <meta name="is-dotcom" content="true">
    <meta name="hostname" content="github.com">
    <meta name="user-login" content="slimina">

    
    <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="gunSapPSKNs+E+N2nOjTWffKFrqZyA1oZvRwuNU+TI6Skg7+pK/md4EwGfCdY4uoJEesJ6haSyfWbdF5q3YqXQ==" name="csrf-token" />

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
    <form accept-charset="UTF-8" action="/logout" class="logout-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="cdnwyGJu8+s53vF7a+mp4vEeFqDssxH5RPPO3XuEbOEX2VlwjE44MWFlxKyRbiMGWdePhpyikxDq4FKyeD/9HQ==" /></div>
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
      <form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="mJYa7ZIESIWGomfMD8F5Eb1ZdQt9/O7p+pFFTV9GClaNvl6N2mNcw/3sh84KZdEIfb+v4OMWPwYf9jxHEDXrwA==" /></div>    <input id="repository_id" name="repository_id" type="hidden" value="11816219" />

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

    <form accept-charset="UTF-8" action="/adamlu/javascript-style-guide/unstar" class="js-toggler-form starred js-unstar-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="xDZp/ZmBzqZlWNb8LrT5gTAC0w00rqNp5RTxZGZ1JP6crAFPHhnzOBKDwh2BIkhwHhVCQdaC4w5K3PHIsg+PtQ==" /></div>
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
    <form accept-charset="UTF-8" action="/adamlu/javascript-style-guide/star" class="js-toggler-form unstarred js-star-button" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="5nH+HLOH5InSPXg+iHFNCDhaPZE63sYMebFjnEQrl0GUnVse8A2QSWKP70cFUOVJrzJrvDUByLWEa8GDf4LZgQ==" /></div>
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
          <form accept-charset="UTF-8" action="/adamlu/javascript-style-guide/fork" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="kUHUsOOwNF/OmvsWZe29Cb3i2eDw0MXPo1qW4P6hkzYNudi5VzTX/CQrtQsX/6GMT2y3yDJ5moLRc1AfQq/Qfg==" /></div>
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
          

<a href="/adamlu/javascript-style-guide/blob/3d67486fdaf6b8f6c1cc013c9e60ba1ee518b75b/CSS%20Style%20Guide.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:9d50b61fb415c01f1c1960a53dcec966 -->

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
               href="/adamlu/javascript-style-guide/blob/master/CSS%20Style%20Guide.md"
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
    <span class='repo-root js-repo-root'><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/adamlu/javascript-style-guide" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">javascript-style-guide</span></a></span></span><span class="separator">/</span><strong class="final-path">CSS Style Guide.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="@adamlu" class="avatar" data-user="92850" height="24" src="https://avatars3.githubusercontent.com/u/92850?v=3&amp;s=48" width="24" />
        <span class="author"><a href="/adamlu" rel="author">adamlu</a></span>
        <time datetime="2013-08-02T03:44:00Z" is="relative-time">Aug 2, 2013</time>
        <div class="commit-title">
            <a href="/adamlu/javascript-style-guide/commit/b854fe3eb5f12a06d831173336403321f398de19" class="message" data-pjax="true" title="Modify the css style guide">Modify the css style guide</a>
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
        <a href="/adamlu/javascript-style-guide/raw/master/CSS%20Style%20Guide.md" class="btn btn-sm " id="raw-url">Raw</a>
          <a href="/adamlu/javascript-style-guide/blame/master/CSS%20Style%20Guide.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
        <a href="/adamlu/javascript-style-guide/commits/master/CSS%20Style%20Guide.md" class="btn btn-sm " rel="nofollow">History</a>
      </div>

        <a class="octicon-btn tooltipped tooltipped-nw"
           href="https://windows.github.com"
           aria-label="Open this file in GitHub for Windows">
            <span class="octicon octicon-device-desktop"></span>
        </a>

            <form accept-charset="UTF-8" action="/adamlu/javascript-style-guide/edit/master/CSS%20Style%20Guide.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="pC6rqCfGBAaFIhJxyQ5fbSqrTdcgANL9NiSPiRxKpAbaf+1+uBy52lzLHzecYKDB0I0QF1qBLWl+DPMb7XpFyQ==" /></div>
              <button class="octicon-btn tooltipped tooltipped-n" type="submit" aria-label="Clicking this button will fork this project so you can edit the file" data-hotkey="e" data-disable-with>
                <span class="octicon octicon-pencil"></span>
              </button>
</form>
          <form accept-charset="UTF-8" action="/adamlu/javascript-style-guide/delete/master/CSS%20Style%20Guide.md" class="inline-form" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="SR4+2LIXFohb5zVeoiS3ufvzxbqkGnqo74+l13Y36QQdwPb/tkXPryHJJSbpMaUMu4fsFtLPOjunaiKdoR+b0A==" /></div>
            <button class="octicon-btn octicon-btn-danger tooltipped tooltipped-n" type="submit" aria-label="Fork this project and delete file" data-disable-with>
              <span class="octicon octicon-trashcan"></span>
            </button>
</form>    </div>

    <div class="file-info">
        410 lines (271 sloc)
        <span class="file-info-divider"></span>
      20.128 kb
    </div>
  </div>
    <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><p>原文：<a href="https://github.com/csswizardry/CSS-Guidelines">https://github.com/csswizardry/CSS-Guidelines</a> 和 <a href="https://github.com/chadluo/CSS-Guidelines/blob/master/README.md">https://github.com/chadluo/CSS-Guidelines/blob/master/README.md</a></p>

<p>注：我根据自己的开发习惯修改和删除了部分规范</p>

<h1>
<a id="user-content-css编码规范" class="anchor" href="#css%E7%BC%96%E7%A0%81%E8%A7%84%E8%8C%83" aria-hidden="true"><span class="octicon octicon-link"></span></a>CSS编码规范</h1>

<p>在参与规模庞大、历时漫长且参与人数众多的项目时，所有开发者遵守如下规则极为重要：</p>

<ul class="task-list">
<li><strong>保持 CSS 便于维护</strong></li>
<li><strong>保持代码清晰易懂</strong></li>
<li><strong>保持代码的可拓展性</strong></li>
</ul>

<p>为了实现这一目标，我们要采用诸多方法。</p>

<p>本文档第一部分将探讨语法、格式以及分析 CSS 结构；第二部分将围绕方法论、思维框架以及编写与规划 CSS 的态度。</p>

<h2>
<a id="user-content-目录" class="anchor" href="#%E7%9B%AE%E5%BD%95" aria-hidden="true"><span class="octicon octicon-link"></span></a>目录</h2>

<p><strong>第一部分</strong></p>

<ul class="task-list">
<li>
<a href="#css-%E6%96%87%E6%A1%A3%E5%88%86%E6%9E%90">CSS 文档分析</a>

<ul class="task-list">
<li><a href="#%E6%80%BB%E5%88%99">总则</a></li>
<li><a href="#%E5%8D%95%E4%B8%80%E6%96%87%E4%BB%B6%E4%B8%8E%E5%A4%9A%E6%96%87%E4%BB%B6">单一文件与多文件</a></li>
<li><a href="#%E7%9B%AE%E5%BD%95-1">目录</a></li>
<li><a href="#%E5%8C%BA%E5%9D%97%E6%A0%87%E9%A2%98">区块标题</a></li>
</ul>
</li>
<li><a href="#%E4%BB%A3%E7%A0%81%E9%A1%BA%E5%BA%8F">代码顺序</a></li>
<li><a href="#css-%E8%A7%84%E5%88%99%E9%9B%86%E5%88%86%E6%9E%90">CSS 规则集分析</a></li>
<li>
<a href="#%E5%91%BD%E5%90%8D%E8%A7%84%E8%8C%83">命名规范</a>

<ul class="task-list">
<li><a href="#javascript-%E9%92%A9%E5%AD%90">JavaScript 钩子</a></li>
<li><a href="#i18n">I18n</a></li>
</ul>
</li>
<li>
<a href="#%E6%B3%A8%E9%87%8A">注释</a>

<ul class="task-list">
<li>
<a href="#%E6%B3%A8%E9%87%8A%E7%9A%84%E6%8B%93%E5%B1%95%E7%94%A8%E6%B3%95">注释的拓展用法</a>

<ul class="task-list">
<li><a href="#%E5%87%86%E4%BF%AE%E9%A5%B0%E9%80%89%E6%8B%A9%E5%99%A8">准修饰选择器</a></li>
<li><a href="#%E4%BB%A3%E7%A0%81%E6%A0%87%E7%AD%BE">代码标签</a></li>
<li><a href="#%E7%BB%A7%E6%89%BF%E6%A0%87%E8%AE%B0">继承标记</a></li>
</ul>
</li>
</ul>
</li>
</ul>

<p><strong>第二部分</strong></p>

<ul class="task-list">
<li><a href="#%E7%BC%96%E5%86%99-css">编写 CSS</a></li>
<li><a href="#%E7%BC%96%E5%86%99%E6%96%B0%E7%BB%84%E4%BB%B6">编写新组件</a></li>
<li><a href="#%E9%9D%A2%E5%90%91%E5%AF%B9%E8%B1%A1-css">面向对象 CSS</a></li>
<li><a href="#%E5%B8%83%E5%B1%80">布局</a></li>
<li>
<a href="#ui-%E5%B0%BA%E5%AF%B8">UI 尺寸</a>

<ul class="task-list">
<li><a href="#%E5%AD%97%E5%8F%B7">字号</a></li>
</ul>
</li>
<li><a href="#%E7%AE%80%E5%86%99">简写</a></li>
<li><a href="#id">ID</a></li>
<li>
<a href="#%E9%80%89%E6%8B%A9%E5%99%A8">选择器</a>

<ul class="task-list">
<li><a href="#%E8%BF%87%E5%BA%A6%E4%BF%AE%E9%A5%B0%E7%9A%84%E9%80%89%E6%8B%A9%E5%99%A8">过修饰选择器</a></li>
<li><a href="#%E9%80%89%E6%8B%A9%E5%99%A8%E6%80%A7%E8%83%BD">选择器性能</a></li>
</ul>
</li>
<li><a href="#%E4%BD%BF%E7%94%A8-css-%E9%80%89%E6%8B%A9%E5%99%A8%E7%9A%84%E7%9B%AE%E7%9A%84">使用 CSS 选择器的目的</a></li>
<li><a href="#important"><code>!important</code></a></li>
<li><a href="#%E9%AD%94%E6%95%B0%E4%B8%8E%E7%BB%9D%E5%AF%B9%E5%AE%9A%E4%BD%8D">魔数与绝对定位</a></li>
<li><a href="#%E6%9D%A1%E4%BB%B6%E5%88%A4%E6%96%AD">条件判断</a></li>
<li><a href="#debugging">Debugging</a></li>
<li><a href="#css-%E9%A2%84%E5%A4%84%E7%90%86%E5%99%A8">CSS 预处理器</a></li>
</ul>

<hr>

<h2>
<a id="user-content-css-文档分析" class="anchor" href="#css-%E6%96%87%E6%A1%A3%E5%88%86%E6%9E%90" aria-hidden="true"><span class="octicon octicon-link"></span></a>CSS 文档分析</h2>

<p>无论编写什么文档，我们都应当尽力维持统一的风格，包括统一的注释、统一的语法与统一的命名规范。</p>

<h3>
<a id="user-content-总则" class="anchor" href="#%E6%80%BB%E5%88%99" aria-hidden="true"><span class="octicon octicon-link"></span></a>总则</h3>

<p>尽量将行宽控制在 80 字节以下。渐变（gradient）相关的语法以及注释中的 URL 等可以算作例外，毕竟这部分我们也无能为力。</p>

<p>我倾向于用 4 个空格而非 Tab 缩进，并且将声明拆分成多行。</p>

<h3>
<a id="user-content-单一文件与多文件" class="anchor" href="#%E5%8D%95%E4%B8%80%E6%96%87%E4%BB%B6%E4%B8%8E%E5%A4%9A%E6%96%87%E4%BB%B6" aria-hidden="true"><span class="octicon octicon-link"></span></a>单一文件与多文件</h3>

<p>有人喜欢在一份文件文件中编写所有的内容，而我在迁移至 Sass 之后开始将样式拆分成多个小文件。这都是很好的做法。无论你选择哪种，下文的规则都将适用，而且如果你遵守这些规则的话你也不会遇到什么问题。这两种写法的区别仅仅在于目录以及区块标题。</p>

<h3>
<a id="user-content-目录-1" class="anchor" href="#%E7%9B%AE%E5%BD%95-1" aria-hidden="true"><span class="octicon octicon-link"></span></a>目录</h3>

<p>在 CSS 的开头，我会写一份目录，例如：</p>

<pre><code>/*------------------------------------*\
    $CONTENTS
\*------------------------------------*/
/**
 * CONTENTS............You’re reading it!
 * RESET...............Set our reset defaults
 * FONT-FACE...........Import brand font files
 */
</code></pre>

<p>这份目录可以告诉其他开发者这个文件中具体含有哪些内容。这份目录中的每一项都与其对应的区块标题相同。</p>

<p>如果你在维护一份单文件 CSS，对应的区块将也在同一文件中。如果你是在编写一组小文件，那么目录中的每一项应当对应相应的 @include 语句。</p>

<h3>
<a id="user-content-区块标题" class="anchor" href="#%E5%8C%BA%E5%9D%97%E6%A0%87%E9%A2%98" aria-hidden="true"><span class="octicon octicon-link"></span></a>区块标题</h3>

<p>目录应当对应区块的标题。请看如下示例：</p>

<pre><code>/*------------------------------------*\
    $RESET
\*------------------------------------*/
</code></pre>

<p>区块标题前缀 <code>$</code> 可以让我们使用 [Cmd|Ctrl]+F 命令查找标题名的同时<strong>将搜索范围限制在区块标题中</strong>。</p>

<p>如果你在维护一份大文件，那么在区块之间空 5 行，如下：</p>

<pre><code>/*------------------------------------*\
    $RESET
\*------------------------------------*/
[Our
reset
styles]



/*------------------------------------*\
    $FONT-FACE
\*------------------------------------*/
</code></pre>

<p>在大文件中快速翻动时这些大块的空档有助于区分区块。</p>

<p>如果你在维护多份、以 @include 连接的 CSS 的话，在每份文件头加上标题即可，不必这样空行。</p>

<h2>
<a id="user-content-代码顺序" class="anchor" href="#%E4%BB%A3%E7%A0%81%E9%A1%BA%E5%BA%8F" aria-hidden="true"><span class="octicon octicon-link"></span></a>代码顺序</h2>

<p>尽量按照特定顺序编写规则，这将确保你充分发挥 CSS 缩写中第一个 <i>C</i> 的意义：cascade，层叠。</p>

<p>一份规划良好的 CSS 应当按照如下排列：</p>

<ol class="task-list">
<li>
<strong>Reset</strong> 万物之根源</li>
<li>
<strong>元素类型</strong> 没有 class 的 <code>h1</code>、<code>ul</code> 等</li>
<li>
<strong>对象以及抽象内容</strong> 最一般、最基础的设计模式</li>
<li>
<strong>子元素</strong> 由对象延伸出来的所有拓展及其子元素</li>
<li>
<strong>修补</strong> 针对异常状态</li>
</ol>

<p>如此一来，当你依次编写 CSS 时，每个区块都可以自动继承在它之前区块的属性。这样就可以减少代码相互抵消的部分，减少某些特殊的问题，组成更理想的 CSS 结构。</p>

<p>关于这方面的更多信息，强烈推荐 Jonathan Snook 的 <a href="http://smacss.com">SMACSS</a>。</p>

<h2>
<a id="user-content-css-规则集分析" class="anchor" href="#css-%E8%A7%84%E5%88%99%E9%9B%86%E5%88%86%E6%9E%90" aria-hidden="true"><span class="octicon octicon-link"></span></a>CSS 规则集分析</h2>

<pre><code>[selector]{
    [property]:[value];
    [&lt;- Declaration -&gt;]
}

[选择器]{
    [属性]:[值];
    [&lt;- 声明 -&gt;]
}
</code></pre>

<p>编写 CSS 样式时，我习惯遵守这些规则：</p>

<ul class="task-list">
<li>class 名称以连字符（-）连接，除了下文提到的 BEM 命名法；</li>
<li>声明拆分成多行；</li>
<li>声明以相关性顺序排列，而非字母顺序；</li>
<li>有前缀的声明适当缩进，从而对齐其值；</li>
<li>缩进样式从而反映 DOM；</li>
<li>保留最后一条声明结尾的分号。</li>
</ul>

<p>例如：</p>

<pre><code>.widget{
    padding:10px;
    border:1px solid #BADA55;
    background-color:#C0FFEE;
    -webkit-border-radius:4px;
       -moz-border-radius:4px;
            border-radius:4px;
}
.widget-heading{
    font-size:1.5rem;
    line-height:1;
    font-weight:bold;
    color:#BADA55;
    margin-right:-10px;
    margin-left: -10px;
    padding:0.25em;
}
</code></pre>

<p>我们还可以发现 <code>.widget-heading</code> 的声明是根据其相关性排列的：<code>.widget-heading</code> 是行间元素，所以我们先添加字体相关的样式声明，接下来是其它的。</p>

<p>以下是一个没有拆分成多行的例子：</p>

<pre><code>.t10    { width:10% }
.t20    { width:20% }
.t25    { width:25% }       /* 1/4 */
.t30    { width:30% }
.t33    { width:33.333% }   /* 1/3 */
.t40    { width:40% }
.t50    { width:50% }       /* 1/2 */
.t60    { width:60% }
.t66    { width:66.666% }   /* 2/3 */
.t70    { width:70% }
.t75    { width:75% }       /* 3/4*/
.t80    { width:80% }
.t90    { width:90% }
</code></pre>

<p>在这个例子（来自<a href="https://github.com/csswizardry/inuit.css/blob/master/inuit.css/partials/base/_tables.scss#L88">inuit.css’s table grid system</a>）中，将 CSS 放在一行内可以使得代码更紧凑。</p>

<h2>
<a id="user-content-命名规范" class="anchor" href="#%E5%91%BD%E5%90%8D%E8%A7%84%E8%8C%83" aria-hidden="true"><span class="octicon octicon-link"></span></a>命名规范</h2>

<p>一般情况下我都是以连字符（-）连接 class 的名字（例如 <code>.foo-bar</code> 而非 <code>.foo_bar</code> 或 <code>.fooBar</code>）。</p>

<p>你应当确保 class 命名得当，力保一字不多、一字不少；将元素命名抽象化以提高复用性（例如 <code>.ui-list</code>，<code>.media</code>）。由此延伸出去的元素命名则要尽量精准（例如 <code>.user-avatar-link</code>）。不用担心 class 名的数量或长度，因为写得好的代码 gzip 也能有效压缩。</p>

<h3>
<a id="user-content-javascript-钩子" class="anchor" href="#javascript-%E9%92%A9%E5%AD%90" aria-hidden="true"><span class="octicon octicon-link"></span></a>JavaScript 钩子</h3>

<p><strong>千万不要把 CSS 样式用作 JavaScript 钩子。</strong>把 JS 行为与样式混在一起将无法对其分别处理。</p>

<p>如果你要把 JS 和某些标记绑定起来的话，写一个 JS 专用的 class。简单地说就是划定一个前缀 <code>.js-</code> 的命名空间，例如 <code>.js-toggle</code>，<code>.js-drag-and-drop</code>。这意味着我们可以通过 class 同时绑定 JS 和 CSS 而不会因为冲突而引发麻烦。</p>

<pre><code>&lt;th class="is-sortable  js-is-sortable"&gt;
&lt;/th&gt;
</code></pre>

<p>上面的这个标记有两个 class，你可以用其中一个来给这个可排序的表格栏添加样式，用另一个添加排序功能。</p>

<h2>
<a id="user-content-注释" class="anchor" href="#%E6%B3%A8%E9%87%8A" aria-hidden="true"><span class="octicon octicon-link"></span></a>注释</h2>

<p>我使用行宽不超过 80 字节的块状注释：</p>

<pre><code>/**
 * This is a docBlock style comment
 *
 * This is a longer description of the comment, describing the code in more
 * detail. We limit these lines to a maximum of 80 characters in length.
 *
 * We can have markup in the comments, and are encouraged to do so:
 *
   &lt;div class=foo&gt;
       &lt;p&gt;Lorem&lt;/p&gt;
   &lt;/div&gt;
 *
 * We do not prefix lines of code with an asterisk as to do so would inhibit
 * copy and paste.
 */


/**
 * 这是一个文档块（DocBlock）风格的注释。
 *
 * 这里开始是描述更详细、篇幅更长的注释正文。当然，我们要把行宽控制在 80 字以内。
 *
 * 我们可以在注释中嵌入 HTML 标记，而且这也是个不错的办法：
 *
    &lt;div class=foo&gt;
        &lt;p&gt;Lorem&lt;/p&gt;
    &lt;/div&gt;
 *
 * 如果是注释内嵌的标记的话，在它前面不加星号，否则会被复制进去。
 */
</code></pre>

<p>在注释中应当尽量详细描述代码，因为对你来说清晰易懂的内容对其他人可能并非如此。每写一部分代码就要专门写注释以详解。</p>

<h3>
<a id="user-content-注释的拓展用法" class="anchor" href="#%E6%B3%A8%E9%87%8A%E7%9A%84%E6%8B%93%E5%B1%95%E7%94%A8%E6%B3%95" aria-hidden="true"><span class="octicon octicon-link"></span></a>注释的拓展用法</h3>

<p>注释有许多很先进的用法，例如：</p>

<ul class="task-list">
<li>准修饰选择器</li>
<li>代码标签</li>
<li>继承标记</li>
</ul>

<h4>
<a id="user-content-准修饰选择器" class="anchor" href="#%E5%87%86%E4%BF%AE%E9%A5%B0%E9%80%89%E6%8B%A9%E5%99%A8" aria-hidden="true"><span class="octicon octicon-link"></span></a>准修饰选择器</h4>

<p>你应当避免过分修饰选择器，例如如果你能写 <code>.nav{}</code> 就尽量不要写 <code>ul.nav{}</code>。过分修饰选择器将影响性能，影响 class 复用性，增加选择器私有度。这些都是你应当竭力避免的。</p>

<h2>
<a id="user-content-编写-css" class="anchor" href="#%E7%BC%96%E5%86%99-css" aria-hidden="true"><span class="octicon octicon-link"></span></a>编写 CSS</h2>

<p>之前的章节主要探讨如何规划 CSS，这些都是易于量化的规则。本章将探讨更理论化的东西，也将探讨我们的态度与方法。</p>

<h2>
<a id="user-content-编写新组件" class="anchor" href="#%E7%BC%96%E5%86%99%E6%96%B0%E7%BB%84%E4%BB%B6" aria-hidden="true"><span class="octicon octicon-link"></span></a>编写新组件</h2>

<p>编写新组件时，要在着手处理 CSS <strong>之前</strong>写好 HTML 部分。这可以令你准确判断哪些 CSS 属性可以继承，避免重复浪费。</p>

<p>先写标记的话，你就可以关注数据、内容与语义，在这之后再添加需要的 class 和 CSS 样式。</p>

<h2>
<a id="user-content-布局" class="anchor" href="#%E5%B8%83%E5%B1%80" aria-hidden="true"><span class="octicon octicon-link"></span></a>布局</h2>

<p>所有组件都不要声明宽度，而由其亲元素或格栅系统来决定。</p>

<p><strong>坚决不要</strong>声明高度。高度应当仅仅用于尺寸已经固定的东西，例如图片和 CSS Sprite。在 <code>p</code>，<code>ul</code>，<code>div</code> 等元素上不应当声明高度。如果需要的话可以写 <code>line-height</code>，这个更加灵活。</p>

<p>格栅系统应当当作书架来理解。是它们容纳内容，而不是把它们本身当成内容装起来，正如你先搭起书架再把东西放进去。比起声明它们的尺寸，把格栅系统和元素的其它属性分来开处理更有助于布局，也使得我们的前端工作更高效。</p>

<p>你在格栅系统上不应当添加任何样式，他们仅仅是为布局而用。在格栅系统内部再添加样式。在格栅系统中任何情况下都不要添加盒模型相关属性。</p>

<h2>
<a id="user-content-ui-尺寸" class="anchor" href="#ui-%E5%B0%BA%E5%AF%B8" aria-hidden="true"><span class="octicon octicon-link"></span></a>UI 尺寸</h2>

<p>理想情况下，格栅系统应当用百分比设定。如上所述，因为我用格栅系统来固定栏宽和页宽，所以我可以不用理会元素的尺寸。</p>

<p>只在已经固定尺寸的元素上使用 px，包括图片以及尺寸已经用 px 固定的 CSS Sprite。</p>

<h3>
<a id="user-content-字号" class="anchor" href="#%E5%AD%97%E5%8F%B7" aria-hidden="true"><span class="octicon octicon-link"></span></a>字号</h3>

<p>定义一些与格栅系统原理类似的 class 来声明字号。这些 class 可以用于双重标题分级，关于这点请阅读 <a href="http://csswizardry.com/2012/02/pragmatic-practical-font-sizing-in-css">Pragmatic, practical font-sizing in CSS</a>。</p>

<h2>
<a id="user-content-简写" class="anchor" href="#%E7%AE%80%E5%86%99" aria-hidden="true"><span class="octicon octicon-link"></span></a>简写</h2>

<p><strong>CSS 简写应当谨慎使用。</strong></p>

<p>编写像 <code>background:red;</code> 这样的属性的确很省事，但是你这么写的意思其实是同时声明 <code>background-image:none; background-position:top left; background-repeat: repeat; background-color:red;</code>。虽然大多数时候这样不会出什么问题，但是哪怕只出一次问题就值得考虑要不要放弃简写了。这里应当改为 <code>background-color:red;</code>。</p>

<p>类似的，像 <code>margin:0;</code> 这样的声明的确简洁清爽，但是还是应当<strong>尽量写清楚</strong>。如果你只是想修改底边边距，就要具体一些，写成 <code>margin-bottom:0;</code>。</p>

<p>反过来，你需要声明的属性也要写清楚，不要因为简写而波及其它属性。例如如果你只想改掉底部的 <code>margin</code>，那就不要用会把其它边距也清零的 <code>margin:0</code>。</p>

<p>简写虽然是好东西，但是注意切勿滥用。</p>

<h2>
<a id="user-content-id" class="anchor" href="#id" aria-hidden="true"><span class="octicon octicon-link"></span></a>ID</h2>

<p>在我们开始处理选择器之前，牢记这句话：</p>

<p><strong>在 CSS 里尽量不要用 ID。</strong></p>

<p>Class 的优势在于复用性，而且私有度也并不高。私有度非常容易导致问题，所以将其降低就尤为重要。ID 的私有度是 class 的 <strong>255</strong> 倍，所以在 CSS 中尽量不要使用。</p>

<h2>
<a id="user-content-选择器" class="anchor" href="#%E9%80%89%E6%8B%A9%E5%99%A8" aria-hidden="true"><span class="octicon octicon-link"></span></a>选择器</h2>

<p>务必保持选择器简短高效。</p>

<p>通过页面元素位置而定位的选择器并不理想。例如 <code>.sidebar h3 span{}</code> 这样的选择器就是定位过于依赖相对位置，所以把 span 移到 h3 和 sidebar 外面时就很难保持其样式。</p>

<p>结构复杂的选择器将会影响性能。选择器结构越复杂（如 <code>.sidebar h3 span</code> 为三层，<code>.content ul p a</code> 是四层），浏览器的消耗就越大。</p>

<p>尽量使得样式不依赖于其定位，尽量保持选择器简洁清晰。</p>

<p>作为一个整体，选择器应当尽量简短（例如只有一层结构），但是 class 名则不应当过于简略，例如 <code>.user-avatar</code> 就远比 <code>.usr-avt</code> 好。</p>

<p><strong>牢记：</strong>class 无所谓是否语义化；应当关注它们是否合理。不要强调 class 名要符合语义，而要注重使用合理且不会过时的名称。</p>

<h3>
<a id="user-content-过度修饰的选择器" class="anchor" href="#%E8%BF%87%E5%BA%A6%E4%BF%AE%E9%A5%B0%E7%9A%84%E9%80%89%E6%8B%A9%E5%99%A8" aria-hidden="true"><span class="octicon octicon-link"></span></a>过度修饰的选择器</h3>

<p>由前文所述，过度修饰的选择器并不理想。</p>

<p>过度修饰的选择器是指像 <code>div.promo</code> 这样的。很可能你只用 <code>.promo</code> 也能得到相同的效果。当然你可能偶尔会需要用元素类型来修饰 class（例如你写了一个 <code>.error</code> 而且想让它在不同的元素类型中显示效果不一样，例如 <code>.error{ color:red; }</code> <code>div.error{ padding:14px;}</code>），但是大多数时候还是应当尽量避免。</p>

<p>再举一个修饰过度的选择器例子，<code>ul.nav li a{}</code>。如前文所说，我们马上就可以删掉 <code>ul</code> 因为我们知道 <code>.nav</code> 是个列表，然后我们就可以发现 <code>a</code> 一定在 <code>li</code> 中，所以我们就能将这个选择器改写成 <code>.nav a{}</code>。</p>

<h3>
<a id="user-content-选择器性能" class="anchor" href="#%E9%80%89%E6%8B%A9%E5%99%A8%E6%80%A7%E8%83%BD" aria-hidden="true"><span class="octicon octicon-link"></span></a>选择器性能</h3>

<p>虽然浏览器性能日渐提升，渲染 CSS 速度越来越快，但是你还是应当关注效率。使用间断、没有嵌套的选择器，不把全局选择器（<code>*{}</code>）用作核心选择器，避免使用日渐复杂的 CSS3 新选择器可以避免这样的问题。</p>

<p>译注，核心选择器：浏览器解析选择器为从右向左的顺序，最右端的元素是样式生效的元素，是为核心选择器。</p>

<h2>
<a id="user-content-使用-css-选择器的目的" class="anchor" href="#%E4%BD%BF%E7%94%A8-css-%E9%80%89%E6%8B%A9%E5%99%A8%E7%9A%84%E7%9B%AE%E7%9A%84" aria-hidden="true"><span class="octicon octicon-link"></span></a>使用 CSS 选择器的目的</h2>

<p>比起努力运用选择器定位到某元素，更好的办法是直接给你想要添加样式的元素直接添加一个 class。我们以 <code>.header ul{}</code> 这样一个选择器为例。</p>

<p>假定这个 <code>ul</code> 就是这个网站的全站导航，它位于 header 中，而且目前为止是 header 中唯一的 <code>ul</code> 元素。<code>.header ul{}</code> 的确可以生效，但是这样并不是好方法，它很容易过时，而且非常晦涩。如果我们在 header 中再添加一个 <code>ul</code> 的话，它就会套用我们给这个导航部分写的样式，哪怕我们设想的不是这个效果。这意味着我们要么要重构许多代码，要么给后面的 <code>ul</code> 新写许多样式来抵消之前的影响。</p>

<p>你的选择器必须符合你要给这个元素添加样式的原因。思考一下，<strong>「我定位到这个元素，是因为它是 <code>.header</code> 下的 <code>ul</code>，还是因为它是我的网站导航？」</strong>这将决定你应当如何使用选择器。</p>

<p>确保你的核心选择器不是类型选择器，也不是高级对象或抽象选择器。例如你在我们的 CSS 中肯定找不到诸如 <code>.sidebar ul{}</code> 或者 <code>.footer .media{}</code> 这样的选择器。</p>

<p>表达清晰：直接找到你要添加样式的元素，而非其亲元素。不要想当然地认为 HTML 不会改变。<strong>用 CSS 直接命中你需要的元素，而非投机取巧。</strong></p>

<p>完整内容请参考我的文章 <a href="http://csswizardry.com/2012/07/shoot-to-kill-css-selector-intent/">Shoot to kill; CSS selector intent</a></p>

<h2>
<a id="user-content-important" class="anchor" href="#important" aria-hidden="true"><span class="octicon octicon-link"></span></a><code>!important</code>
</h2>

<p>只在起辅助作用的 class 上用 <code>!important</code>。用 <code>!important</code> 提升优先级也可以，例如如果你要让某条规则<strong>一直</strong>生效的话，可以用 <code>.error{ color:red!important; }</code>。</p>

<p>避免主动使用 <code>!important</code>。例如 CSS 写得很复杂时不要用它来取巧，要好好整理并重构之前的部分，保持选择器简短并且避免用 ID 将效果拔群。</p>

<h2>
<a id="user-content-魔数与绝对定位" class="anchor" href="#%E9%AD%94%E6%95%B0%E4%B8%8E%E7%BB%9D%E5%AF%B9%E5%AE%9A%E4%BD%8D" aria-hidden="true"><span class="octicon octicon-link"></span></a>魔数与绝对定位</h2>

<p>魔数（Magic Number）是指那些「凑巧有效果」的数字，这东西非常不好，因为它们只是治标不治本而且缺乏拓展性。</p>

<p>例如 <code>.dropdown-nav li:hover ul{ top:37px; }</code> 把下拉菜单移动下来远非良策，因为这里的 37px 就是个魔数。37px 会生效的原因是因为这时 <code>.dropbox-nav</code> 碰巧高 37px 而已。</p>

<p>这时你应该用 <code>.dropdown-nav li:hover ul{ top:100%; }</code>，也即无论 <code>.dropbox-down</code> 多高，这个下拉菜单都会往下移动 100%。</p>

<p>每当你要在代码中放入数字的时候，请三思而行。如果你能用一个关键字（例如  <code>top:100%</code> 意即「从上面拉到最下面」）替换之，或者有更好的解决方法的话，就尽量避免直接出现数字。</p>

<p>你在 CSS 中留下的每一个数字，都是你许下而不愿遵守的承诺。</p>

<h2>
<a id="user-content-条件判断" class="anchor" href="#%E6%9D%A1%E4%BB%B6%E5%88%A4%E6%96%AD" aria-hidden="true"><span class="octicon octicon-link"></span></a>条件判断</h2>

<p>专门为 IE 写的样式基本上都是可以避免的，唯一需要为 IE 专门处理的是为了处理 IE 不支持的内容（例如 PNG）。</p>

<p>简而言之，如果你重构 CSS 的话，所有的布局和盒模型都不用额外兼容 IE。也就是说你基本上不用 <code>&lt;!--[if IE 7]&gt; element{ margin-left:-9px; } &lt; ![endif]--&gt;</code> 或者类似的兼容 IE 的写法。</p>

<h2>
<a id="user-content-debugging" class="anchor" href="#debugging" aria-hidden="true"><span class="octicon octicon-link"></span></a>Debugging</h2>

<p>如果你要解决 CSS 问题的话，<strong>先把旧代码拿掉再写新的</strong>。如果旧的 CSS 中有问题的话，写新代码是解决不了的。</p>

<p>把 CSS 代码和 HTML 部分删掉，直到没有 BUG 为止，然后你就知道问题出在哪里了。</p>

<p>有时候写上一个 <code>overflow:hidden</code> 或者其它能把问题藏起来的代码的确效果立竿见影，但是 overflow 方面可能根本就没问题。所以<strong>要治本，而不是单纯治标</strong>。</p>

<h2>
<a id="user-content-css-预处理器" class="anchor" href="#css-%E9%A2%84%E5%A4%84%E7%90%86%E5%99%A8" aria-hidden="true"><span class="octicon octicon-link"></span></a>CSS 预处理器</h2>

<p>我用 Sass。使用时应当<strong>灵活运用</strong>。用 Sass 可以令你的 CSS 更强大，但是不要嵌套得太复杂。在 Vanilla CSS 中，只在必要的地方用嵌套即可，例如：</p>

<pre><code>.header{}
.header .site-nav{}
.header .site-nav li{}
.header .site-nav li a{}
</code></pre>

<p>这样的写法在普通 CSS 里完全用不到。以下为<strong>不好的</strong> Sass 写法：</p>

<pre><code>.header{
    .site-nav{
        li{
            a{}
        }
    }
}
</code></pre>

<p>如果你用 Sass 的话，尽量这么写：</p>

<pre><code>.header{}
.site-nav{
    li{}
    a{}
}
</code></pre>
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
      <li>&copy; 2015 <span title="0.06449s from github-fe120-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
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

