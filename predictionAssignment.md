



<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled is-u2f-enabled">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    <meta name="viewport" content="width=1020">
    
    
    <title>MachineLearning/predictionAssignment.md at master · Emaasit/MachineLearning</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="Emaasit/MachineLearning" name="twitter:title" /><meta content="Contribute to MachineLearning development by creating an account on GitHub." name="twitter:description" /><meta content="https://avatars1.githubusercontent.com/u/7738216?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars1.githubusercontent.com/u/7738216?v=3&amp;s=400" property="og:image" /><meta content="Emaasit/MachineLearning" property="og:title" /><meta content="https://github.com/Emaasit/MachineLearning" property="og:url" /><meta content="Contribute to MachineLearning development by creating an account on GitHub." property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    <link rel="web-socket" href="wss://live.github.com/_sockets/OTU2MTY4ODo5NDlkZGJiZmUxZTc4MmI1YmFhNzJhNWRmMWIyZjQ3ZDozNDA1MDhjZjBmYzVlY2E0ZTJmZmVmNDBiNTMwYWFlNGU0NTZhY2NlNmRlNzRlYzY2N2U4NDVmNTA3ZmFhZDk0--d9f2607b36c68f681c4580613a4297a99c117dc8">
    <meta name="pjax-timeout" content="1000">
    <link rel="sudo-modal" href="/sessions/sudo_modal">

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-analytics" content="UA-3769691-2">

<meta content="collector.githubapp.com" name="octolytics-host" /><meta content="github" name="octolytics-app-id" /><meta content="ADE069E3:35CD:31350994:56803795" name="octolytics-dimension-request_id" /><meta content="9561688" name="octolytics-actor-id" /><meta content="kimjarabin" name="octolytics-actor-login" /><meta content="6698e417827477a1ad156f8ea53a00617063fa5693682a705a8198b97e8c9485" name="octolytics-actor-hash" />
<meta content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" name="analytics-location" />
<meta content="Rails, view, blob#show" data-pjax-transient="true" name="analytics-event" />


  <meta class="js-ga-set" name="dimension1" content="Logged In">



        <meta name="hostname" content="github.com">
    <meta name="user-login" content="kimjarabin">

        <meta name="expected-hostname" content="github.com">

      <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#4078c0">
      <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">

    <meta content="dff0b91ac5d2c5ec309a43933c328af70c741469" name="form-nonce" />

    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github-16bf5399d85a6f926eb6af8f983ed5cf907e97b4da4a650dc11920d425826218.css" integrity="sha256-Fr9Tmdhab5Jutq+PmD7Vz5B+l7TaSmUNwRkg1CWCYhg=" media="all" rel="stylesheet" />
    <link crossorigin="anonymous" href="https://assets-cdn.github.com/assets/github2-451ab63ad67fa9af580e5d9a3b2b7de911ce2e4b2437638f26fe8cb3879e67d8.css" integrity="sha256-RRq2OtZ/qa9YDl2aOyt96RHOLkskN2OPJv6Ms4eeZ9g=" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="be269b1951a3572820c1f935e13a2f75">

      
  <meta name="description" content="Contribute to MachineLearning development by creating an account on GitHub.">
  <meta name="go-import" content="github.com/Emaasit/MachineLearning git https://github.com/Emaasit/MachineLearning.git">

  <meta content="7738216" name="octolytics-dimension-user_id" /><meta content="Emaasit" name="octolytics-dimension-user_login" /><meta content="25747857" name="octolytics-dimension-repository_id" /><meta content="Emaasit/MachineLearning" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="25747857" name="octolytics-dimension-repository_network_root_id" /><meta content="Emaasit/MachineLearning" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/Emaasit/MachineLearning/commits/master.atom" rel="alternate" title="Recent Commits to MachineLearning:master" type="application/atom+xml">

  </head>


  <body class="logged_in   env-production macintosh vis-public page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>

    
    
    



      <div class="header header-logged-in true" role="banner">
  <div class="container clearfix">

    <a class="header-logo-invertocat" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <span class="mega-octicon octicon-mark-github "></span>
</a>


      <div class="site-search repo-scope js-site-search" role="search">
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/Emaasit/MachineLearning/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/Emaasit/MachineLearning/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <label class="js-chromeless-input-container form-control">
    <div class="scope-badge">This repository</div>
    <input type="text"
      class="js-site-search-focus js-site-search-field is-clearable chromeless-input"
      data-hotkey="s"
      name="q"
      placeholder="Search"
      aria-label="Search this repository"
      data-global-scope-placeholder="Search GitHub"
      data-repo-scope-placeholder="Search"
      tabindex="1"
      autocapitalize="off">
  </label>
</form>
      </div>

      <ul class="header-nav left" role="navigation">
        <li class="header-nav-item">
          <a href="/pulls" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:pulls context:user" data-hotkey="g p" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls">
            Pull requests
</a>        </li>
        <li class="header-nav-item">
          <a href="/issues" class="js-selected-navigation-item header-nav-link" data-ga-click="Header, click, Nav menu - item:issues context:user" data-hotkey="g i" data-selected-links="/issues /issues/assigned /issues/mentioned /issues">
            Issues
</a>        </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://gist.github.com/" data-ga-click="Header, go to gist, text:gist">Gist</a>
          </li>
      </ul>

    
<ul class="header-nav user-nav right" id="user-links">
  <li class="header-nav-item">
      <span class="js-socket-channel js-updatable-content"
        data-channel="notification-changed:kimjarabin"
        data-url="/notifications/header">
      <a href="/notifications" aria-label="You have no unread notifications" class="header-nav-link notification-indicator tooltipped tooltipped-s" data-ga-click="Header, go to notifications, icon:read" data-hotkey="g n">
          <span class="mail-status all-read"></span>
          <span class="octicon octicon-bell "></span>
</a>  </span>

  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link tooltipped tooltipped-s js-menu-target" href="/new"
       aria-label="Create new…"
       data-ga-click="Header, create new, icon:add">
      <span class="octicon octicon-plus left"></span>
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <ul class="dropdown-menu dropdown-menu-sw">
        
<a class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>


  <a class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <div class="dropdown-divider"></div>
  <div class="dropdown-header">
    <span title="Emaasit/MachineLearning">This repository</span>
  </div>
    <a class="dropdown-item" href="/Emaasit/MachineLearning/issues/new" data-ga-click="Header, create new issue">
      New issue
    </a>

      </ul>
    </div>
  </li>

  <li class="header-nav-item dropdown js-menu-container">
    <a class="header-nav-link name tooltipped tooltipped-sw js-menu-target" href="/kimjarabin"
       aria-label="View profile and more"
       data-ga-click="Header, show menu, icon:avatar">
      <img alt="@kimjarabin" class="avatar" height="20" src="https://avatars0.githubusercontent.com/u/9561688?v=3&amp;s=40" width="20" />
      <span class="dropdown-caret"></span>
    </a>

    <div class="dropdown-menu-content js-menu-content">
      <div class="dropdown-menu  dropdown-menu-sw">
        <div class=" dropdown-header header-nav-current-user css-truncate">
            Signed in as <strong class="css-truncate-target">kimjarabin</strong>

        </div>


        <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/kimjarabin" data-ga-click="Header, go to profile, text:your profile">
            Your profile
          </a>
        <a class="dropdown-item" href="/stars" data-ga-click="Header, go to starred repos, text:your stars">
          Your stars
        </a>
        <a class="dropdown-item" href="/explore" data-ga-click="Header, go to explore, text:explore">
          Explore
        </a>
          <a class="dropdown-item" href="/integrations" data-ga-click="Header, go to integrations, text:integrations">
            Integrations
          </a>
        <a class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">
          Help
        </a>

          <div class="dropdown-divider"></div>

          <a class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">
            Settings
          </a>

          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/logout" class="logout-form" data-form-nonce="dff0b91ac5d2c5ec309a43933c328af70c741469" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="lH3X7/2Mo2MSvSP6YbezOFLKZEgvil+Vc+yEq6VzRgm/sGMQTHdGND69c8fu1ct9yGvCDul/awgU5IVggCUyLw==" /></div>
            <button class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout">
              Sign out
            </button>
</form>
      </div>
    </div>
  </li>
</ul>


    
  </div>
</div>

      

      


    <div id="start-of-content" class="accessibility-aid"></div>

      <div id="js-flash-container">
</div>


    <div role="main" class="main-content">
        <div itemscope itemtype="http://schema.org/WebPage">
    <div id="js-repo-pjax-container" class="context-loader-container js-repo-nav-next" data-pjax-container>
      
<div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav">
  <div class="container repohead-details-container">

    

<ul class="pagehead-actions">

  <li>
        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/notifications/subscribe" class="js-social-container" data-autosubmit="true" data-form-nonce="dff0b91ac5d2c5ec309a43933c328af70c741469" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="3B+RaQ54KtF+UE7upJQm5BsCCLAegWQaikXYWYvtA7J/c4QKsL24KyadYVVSLYy6QSaSu6M8P2QlAhU2Ceiq2g==" /></div>      <input id="repository_id" name="repository_id" type="hidden" value="25747857" />

        <div class="select-menu js-menu-container js-select-menu">
          <a href="/Emaasit/MachineLearning/subscription"
            class="btn btn-sm btn-with-count select-menu-button js-menu-target" role="button" tabindex="0" aria-haspopup="true"
            data-ga-click="Repository, click Watch settings, action:blob#show">
            <span class="js-select-button">
              <span class="octicon octicon-eye "></span>
              Watch
            </span>
          </a>
          <a class="social-count js-social-count" href="/Emaasit/MachineLearning/watchers">
            1
          </a>

        <div class="select-menu-modal-holder">
          <div class="select-menu-modal subscription-menu-modal js-menu-content" aria-hidden="true">
            <div class="select-menu-header">
              <span aria-label="Close" class="octicon octicon-x js-menu-close" role="button"></span>
              <span class="select-menu-title">Notifications</span>
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

    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/Emaasit/MachineLearning/unstar" class="js-toggler-form starred js-unstar-button" data-form-nonce="dff0b91ac5d2c5ec309a43933c328af70c741469" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="5eIfqg1HH6Rke/b7X3Nf//9OfKd/QEVEnnBW5cgYCk33LYfkumvEbC9AKWTH6oczbs9r9yKGL0CcwXOi+ppsdw==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Unstar this repository" title="Unstar Emaasit/MachineLearning"
        data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">
        <span class="octicon octicon-star "></span>
        Unstar
      </button>
        <a class="social-count js-social-count" href="/Emaasit/MachineLearning/stargazers">
          0
        </a>
</form>
    <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/Emaasit/MachineLearning/star" class="js-toggler-form unstarred js-star-button" data-form-nonce="dff0b91ac5d2c5ec309a43933c328af70c741469" data-remote="true" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="WDi4i+qmt8dk1nNBmiyQ1/iYt9nkmzXozLIag3XslgI/a9qIrwn+MLaYECCC/UFoRV1JjhodLv/HCk0Ni7Cjxw==" /></div>
      <button
        class="btn btn-sm btn-with-count js-toggler-target"
        aria-label="Star this repository" title="Star Emaasit/MachineLearning"
        data-ga-click="Repository, click star button, action:blob#show; text:Star">
        <span class="octicon octicon-star "></span>
        Star
      </button>
        <a class="social-count js-social-count" href="/Emaasit/MachineLearning/stargazers">
          0
        </a>
</form>  </div>

  </li>

  <li>
          <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/Emaasit/MachineLearning/fork" class="btn-with-count" data-form-nonce="dff0b91ac5d2c5ec309a43933c328af70c741469" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="2EZhKqnK3S8bycp2sclEETjGGwRRntMfOXQtjXkEbfQWcWTlirghZghyrrlA1Ol6NQwGctI04+mwo++OMuFplg==" /></div>
            <button
                type="submit"
                class="btn btn-sm btn-with-count"
                data-ga-click="Repository, show fork modal, action:blob#show; text:Fork"
                title="Fork your own copy of Emaasit/MachineLearning to your account"
                aria-label="Fork your own copy of Emaasit/MachineLearning to your account">
              <span class="octicon octicon-repo-forked "></span>
              Fork
            </button>
</form>
    <a href="/Emaasit/MachineLearning/network" class="social-count">
      5
    </a>
  </li>
</ul>

    <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public ">
  <span class="octicon octicon-repo "></span>
  <span class="author"><a href="/Emaasit" class="url fn" itemprop="url" rel="author"><span itemprop="title">Emaasit</span></a></span><!--
--><span class="path-divider">/</span><!--
--><strong><a href="/Emaasit/MachineLearning" data-pjax="#js-repo-pjax-container">MachineLearning</a></strong>

  <span class="page-context-loader">
    <img alt="" height="16" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32.gif" width="16" />
  </span>

</h1>

  </div>
  <div class="container">
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <a href="/Emaasit/MachineLearning" aria-label="Code" aria-selected="true" class="js-selected-navigation-item selected reponav-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /Emaasit/MachineLearning">
    <span class="octicon octicon-code "></span>
    Code
</a>
    <a href="/Emaasit/MachineLearning/issues" class="js-selected-navigation-item reponav-item" data-hotkey="g i" data-selected-links="repo_issues repo_labels repo_milestones /Emaasit/MachineLearning/issues">
      <span class="octicon octicon-issue-opened "></span>
      Issues
      <span class="counter">0</span>
</a>
  <a href="/Emaasit/MachineLearning/pulls" class="js-selected-navigation-item reponav-item" data-hotkey="g p" data-selected-links="repo_pulls /Emaasit/MachineLearning/pulls">
    <span class="octicon octicon-git-pull-request "></span>
    Pull requests
    <span class="counter">0</span>
</a>
    <a href="/Emaasit/MachineLearning/wiki" class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /Emaasit/MachineLearning/wiki">
      <span class="octicon octicon-book "></span>
      Wiki
</a>
  <a href="/Emaasit/MachineLearning/pulse" class="js-selected-navigation-item reponav-item" data-selected-links="pulse /Emaasit/MachineLearning/pulse">
    <span class="octicon octicon-pulse "></span>
    Pulse
</a>
  <a href="/Emaasit/MachineLearning/graphs" class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors /Emaasit/MachineLearning/graphs">
    <span class="octicon octicon-graph "></span>
    Graphs
</a>

</nav>

  </div>
</div>

<div class="container new-discussion-timeline experiment-repo-nav">
  <div class="repository-content">

    

<a href="/Emaasit/MachineLearning/blob/51ffa890746a81fa8939c8b80cfbc9e0076444ab/predictionAssignment.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:902a2843c1ac549b702e4502bfddcd67 -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <button class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    title="master"
    type="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <i>Branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span aria-label="Close" class="octicon octicon-x js-menu-close" role="button"></span>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open "
               href="/Emaasit/MachineLearning/blob/gh-pages/predictionAssignment.md"
               data-name="gh-pages"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="gh-pages">
                gh-pages
              </span>
            </a>
            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/Emaasit/MachineLearning/blob/master/predictionAssignment.md"
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
    <a href="/Emaasit/MachineLearning/find/master"
          class="js-show-file-finder btn btn-sm"
          data-pjax
          data-hotkey="t">
      Find file
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button">Copy path</button>
  </div>
  <div class="breadcrumb js-zeroclipboard-target">
    <span class="repo-root js-repo-root"><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/Emaasit/MachineLearning" class="" data-branch="master" data-pjax="true" itemscope="url"><span itemprop="title">MachineLearning</span></a></span></span><span class="separator">/</span><strong class="final-path">predictionAssignment.md</strong>
  </div>
</div>


  <div class="commit-tease">
      <span class="right">
        <a class="commit-tease-sha" href="/Emaasit/MachineLearning/commit/2c171f31b6727ea06b126fbe4d6600dbb3971372" data-pjax>
          2c171f3
        </a>
        <time datetime="2014-10-26T02:25:18Z" is="relative-time">Oct 25, 2014</time>
      </span>
      <div>
        <img alt="@Emaasit" class="avatar" height="20" src="https://avatars2.githubusercontent.com/u/7738216?v=3&amp;s=40" width="20" />
        <a href="/Emaasit" class="user-mention" rel="author">Emaasit</a>
          <a href="/Emaasit/MachineLearning/commit/2c171f31b6727ea06b126fbe4d6600dbb3971372" class="message" data-pjax="true" title="updated the html">updated the html</a>
      </div>

    <div class="commit-tease-contributors">
      <a class="muted-link contributors-toggle" href="#blob_contributors_box" rel="facebox">
        <strong>1</strong>
         contributor
      </a>
      
    </div>

    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header" data-facebox-id="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list" data-facebox-id="facebox-description">
          <li class="facebox-user-list-item">
            <img alt="@Emaasit" height="24" src="https://avatars0.githubusercontent.com/u/7738216?v=3&amp;s=48" width="24" />
            <a href="/Emaasit">Emaasit</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
  <div class="file-actions">

    <div class="btn-group">
      <a href="/Emaasit/MachineLearning/raw/master/predictionAssignment.md" class="btn btn-sm " id="raw-url">Raw</a>
        <a href="/Emaasit/MachineLearning/blame/master/predictionAssignment.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
      <a href="/Emaasit/MachineLearning/commits/master/predictionAssignment.md" class="btn btn-sm " rel="nofollow">History</a>
    </div>

        <a class="octicon-btn tooltipped tooltipped-nw"
           href="https://mac.github.com"
           aria-label="Open this file in GitHub Desktop"
           data-ga-click="Repository, open with desktop, type:mac">
            <span class="octicon octicon-device-desktop "></span>
        </a>

        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/Emaasit/MachineLearning/edit/master/predictionAssignment.md" class="inline-form js-update-url-with-hash" data-form-nonce="dff0b91ac5d2c5ec309a43933c328af70c741469" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="/bqpex9nJu097g14dFvOxEjDuLLbIEOqbovvNEDek4nI92VYdnQ/1JZinFAPrw0vgXFs1hzvUyMFFAuREdCcmg==" /></div>
          <button class="octicon-btn tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and edit the file" data-hotkey="e" data-disable-with>
            <span class="octicon octicon-pencil "></span>
          </button>
</form>        <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="/Emaasit/MachineLearning/delete/master/predictionAssignment.md" class="inline-form" data-form-nonce="dff0b91ac5d2c5ec309a43933c328af70c741469" method="post"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /><input name="authenticity_token" type="hidden" value="hUkBHbEWmzaF41s/f7yVwxKTuutLrDxUizLZE3/BHUfE/aB1UzWkTOYj8Nah7W1h8q/oscmZQREnF+Xv1s6DCw==" /></div>
          <button class="octicon-btn octicon-btn-danger tooltipped tooltipped-nw" type="submit"
            aria-label="Fork this project and delete the file" data-disable-with>
            <span class="octicon octicon-trashcan "></span>
          </button>
</form>  </div>

  <div class="file-info">
      628 lines (495 sloc)
      <span class="file-info-divider"></span>
    19.3 KB
  </div>
</div>

  
  <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1><a id="user-content-practical-machine-learning-prediction-project" class="anchor" href="#practical-machine-learning-prediction-project" aria-hidden="true"><span class="octicon octicon-link"></span></a>Practical Machine Learning Prediction Project</h1>

<p>Daniel Emaasit <a href="https://github.com/emaasit/MachineLearning">GitHub</a>  </p>

<pre><code>## Run time: 2014-10-25 19:02:13
## R version: R version 3.0.2 (2013-09-25)
</code></pre>

<blockquote>
<p><strong>Background</strong></p>

<p>Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement - a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it. In this project, your goal will be to use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways. More information is available from the website here: <a href="http://groupware.les.inf.puc-rio.br/har">http://groupware.les.inf.puc-rio.br/har</a> (see the section on the Weight Lifting Exercise Dataset). </p>

<p>*<em>Data *</em></p>

<p>The training data for this project are available here: </p>

<p><a href="https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv">https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv</a></p>

<p>The test data are available here: </p>

<p><a href="https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv">https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv</a></p>

<p>The data for this project come from this source: <a href="http://groupware.les.inf.puc-rio.br/har">http://groupware.les.inf.puc-rio.br/har</a>. If you use the document you create for this class for any purpose please cite them as they have been very generous in allowing their data to be used for this kind of assignment. </p>

<p><strong>What you should submit</strong></p>

<p>The goal of your project is to predict the manner in which they did the exercise. This is the "classe" variable in the training set. You may use any of the other variables to predict with. You should create a report describing how you built your model, how you used cross validation, what you think the expected out of sample error is, and why you made the choices you did. You will also use your prediction model to predict 20 different test cases. </p>

<ol>
<li>Your submission should consist of a link to a Github repo with your R markdown and compiled HTML file describing your analysis. Please constrain the text of the writeup to &lt; 2000 words and the number of figures to be less than 5. It will make it easier for the graders if you submit a repo with a gh-pages branch so the HTML page can be viewed online (and you always want to make it easy on graders :-).</li>
<li>You should also apply your machine learning algorithm to the 20 test cases available in the test data above. Please submit your predictions in appropriate format to the programming assignment for automated grading. See the programming assignment for additional details. </li>
</ol>

<p>*<em>Reproducibility *</em></p>

<p>Due to security concerns with the exchange of R code, your code will not be run during the evaluation by your classmates. Please be sure that if they download the repo, they will be able to view the compiled HTML version of your analysis. </p>
</blockquote>

<h1><a id="user-content-prepare-the-datasets" class="anchor" href="#prepare-the-datasets" aria-hidden="true"><span class="octicon octicon-link"></span></a>Prepare the datasets</h1>

<p>Load the training data into a data table.</p>

<div class="highlight highlight-source-r"><pre>library(<span class="pl-smi">data.table</span>)</pre></div>

<pre><code>## Warning: package 'data.table' was built under R version 3.0.3
</code></pre>

<div class="highlight highlight-source-r"><pre>setInternet2(<span class="pl-c1">TRUE</span>)
<span class="pl-smi">url</span> <span class="pl-k">&lt;-</span> <span class="pl-s"><span class="pl-pds">"</span>https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv<span class="pl-pds">"</span></span>
<span class="pl-smi">D</span> <span class="pl-k">&lt;-</span> fread(<span class="pl-smi">url</span>)</pre></div>

<p>Load the testing data into a data table.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">url</span> <span class="pl-k">&lt;-</span> <span class="pl-s"><span class="pl-pds">"</span>https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv<span class="pl-pds">"</span></span>
<span class="pl-smi">DTest</span> <span class="pl-k">&lt;-</span> fread(<span class="pl-smi">url</span>)</pre></div>

<p>Which variables in the test dataset have zero <code>NA</code>s?
Use this tip: <a href="http://stackoverflow.com/a/11330265">finding columns with all missing values in r</a>.</p>

<p>Belt, arm, dumbbell, and forearm variables that do not have any missing values in the test dataset will be <strong>predictor candidates</strong>.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">isAnyMissing</span> <span class="pl-k">&lt;-</span> sapply(<span class="pl-smi">DTest</span>, <span class="pl-k">function</span> (<span class="pl-smi">x</span>) any(is.na(<span class="pl-smi">x</span>) <span class="pl-k">|</span> <span class="pl-smi">x</span> <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>))
<span class="pl-smi">isPredictor</span> <span class="pl-k">&lt;-</span> <span class="pl-k">!</span><span class="pl-smi">isAnyMissing</span> <span class="pl-k">&amp;</span> grepl(<span class="pl-s"><span class="pl-pds">"</span>belt|[^(fore)]arm|dumbbell|forearm<span class="pl-pds">"</span></span>, names(<span class="pl-smi">isAnyMissing</span>))
<span class="pl-smi">predCandidates</span> <span class="pl-k">&lt;-</span> names(<span class="pl-smi">isAnyMissing</span>)[<span class="pl-smi">isPredictor</span>]
<span class="pl-smi">predCandidates</span></pre></div>

<pre><code>##  [1] "roll_belt"            "pitch_belt"           "yaw_belt"            
##  [4] "total_accel_belt"     "gyros_belt_x"         "gyros_belt_y"        
##  [7] "gyros_belt_z"         "accel_belt_x"         "accel_belt_y"        
## [10] "accel_belt_z"         "magnet_belt_x"        "magnet_belt_y"       
## [13] "magnet_belt_z"        "roll_arm"             "pitch_arm"           
## [16] "yaw_arm"              "total_accel_arm"      "gyros_arm_x"         
## [19] "gyros_arm_y"          "gyros_arm_z"          "accel_arm_x"         
## [22] "accel_arm_y"          "accel_arm_z"          "magnet_arm_x"        
## [25] "magnet_arm_y"         "magnet_arm_z"         "roll_dumbbell"       
## [28] "pitch_dumbbell"       "yaw_dumbbell"         "total_accel_dumbbell"
## [31] "gyros_dumbbell_x"     "gyros_dumbbell_y"     "gyros_dumbbell_z"    
## [34] "accel_dumbbell_x"     "accel_dumbbell_y"     "accel_dumbbell_z"    
## [37] "magnet_dumbbell_x"    "magnet_dumbbell_y"    "magnet_dumbbell_z"   
## [40] "roll_forearm"         "pitch_forearm"        "yaw_forearm"         
## [43] "total_accel_forearm"  "gyros_forearm_x"      "gyros_forearm_y"     
## [46] "gyros_forearm_z"      "accel_forearm_x"      "accel_forearm_y"     
## [49] "accel_forearm_z"      "magnet_forearm_x"     "magnet_forearm_y"    
## [52] "magnet_forearm_z"
</code></pre>

<p>Subset the primary dataset to include only the <strong>predictor candidates</strong> and the outcome variable, <code>classe</code>.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">varToInclude</span> <span class="pl-k">&lt;-</span> c(<span class="pl-s"><span class="pl-pds">"</span>classe<span class="pl-pds">"</span></span>, <span class="pl-smi">predCandidates</span>)
<span class="pl-smi">D</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">D</span>[, <span class="pl-smi">varToInclude</span>, <span class="pl-v">with</span><span class="pl-k">=</span><span class="pl-c1">FALSE</span>]
dim(<span class="pl-smi">D</span>)</pre></div>

<pre><code>## [1] 19622    53
</code></pre>

<div class="highlight highlight-source-r"><pre>names(<span class="pl-smi">D</span>)</pre></div>

<pre><code>##  [1] "classe"               "roll_belt"            "pitch_belt"          
##  [4] "yaw_belt"             "total_accel_belt"     "gyros_belt_x"        
##  [7] "gyros_belt_y"         "gyros_belt_z"         "accel_belt_x"        
## [10] "accel_belt_y"         "accel_belt_z"         "magnet_belt_x"       
## [13] "magnet_belt_y"        "magnet_belt_z"        "roll_arm"            
## [16] "pitch_arm"            "yaw_arm"              "total_accel_arm"     
## [19] "gyros_arm_x"          "gyros_arm_y"          "gyros_arm_z"         
## [22] "accel_arm_x"          "accel_arm_y"          "accel_arm_z"         
## [25] "magnet_arm_x"         "magnet_arm_y"         "magnet_arm_z"        
## [28] "roll_dumbbell"        "pitch_dumbbell"       "yaw_dumbbell"        
## [31] "total_accel_dumbbell" "gyros_dumbbell_x"     "gyros_dumbbell_y"    
## [34] "gyros_dumbbell_z"     "accel_dumbbell_x"     "accel_dumbbell_y"    
## [37] "accel_dumbbell_z"     "magnet_dumbbell_x"    "magnet_dumbbell_y"   
## [40] "magnet_dumbbell_z"    "roll_forearm"         "pitch_forearm"       
## [43] "yaw_forearm"          "total_accel_forearm"  "gyros_forearm_x"     
## [46] "gyros_forearm_y"      "gyros_forearm_z"      "accel_forearm_x"     
## [49] "accel_forearm_y"      "accel_forearm_z"      "magnet_forearm_x"    
## [52] "magnet_forearm_y"     "magnet_forearm_z"
</code></pre>

<p>Make <code>classe</code> into a factor.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">D</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">D</span>[, <span class="pl-smi">classe</span> <span class="pl-k">:</span><span class="pl-k">=</span> <span class="pl-k">factor</span>(<span class="pl-smi">D</span>[, <span class="pl-smi">classe</span>])]
<span class="pl-smi">D</span>[, .<span class="pl-smi">N</span>, <span class="pl-smi">classe</span>]</pre></div>

<pre><code>##    classe    N
## 1:      A 5580
## 2:      B 3797
## 3:      C 3422
## 4:      D 3216
## 5:      E 3607
</code></pre>

<p>Split the dataset into a 60% training and 40% probing dataset.</p>

<div class="highlight highlight-source-r"><pre>library(<span class="pl-smi">caret</span>)</pre></div>

<pre><code>## Warning: package 'caret' was built under R version 3.0.3
</code></pre>

<pre><code>## Loading required package: lattice
</code></pre>

<pre><code>## Warning: package 'lattice' was built under R version 3.0.3
</code></pre>

<pre><code>## Loading required package: ggplot2
</code></pre>

<pre><code>## Warning: package 'ggplot2' was built under R version 3.0.3
</code></pre>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">seed</span> <span class="pl-k">&lt;-</span> as.numeric(as.Date(<span class="pl-s"><span class="pl-pds">"</span>2014-10-26<span class="pl-pds">"</span></span>))
set.seed(<span class="pl-smi">seed</span>)
<span class="pl-smi">inTrain</span> <span class="pl-k">&lt;-</span> createDataPartition(<span class="pl-smi">D</span><span class="pl-k">$</span><span class="pl-smi">classe</span>, <span class="pl-v">p</span><span class="pl-k">=</span><span class="pl-c1">0.6</span>)
<span class="pl-smi">DTrain</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">D</span>[<span class="pl-smi">inTrain</span>[[<span class="pl-c1">1</span>]]]
<span class="pl-smi">DProbe</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">D</span>[<span class="pl-k">-</span><span class="pl-smi">inTrain</span>[[<span class="pl-c1">1</span>]]]</pre></div>

<p>Preprocess the prediction variables by centering and scaling.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">X</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">DTrain</span>[, <span class="pl-smi">predCandidates</span>, <span class="pl-v">with</span><span class="pl-k">=</span><span class="pl-c1">FALSE</span>]
<span class="pl-smi">preProc</span> <span class="pl-k">&lt;-</span> preProcess(<span class="pl-smi">X</span>)
<span class="pl-smi">preProc</span></pre></div>

<pre><code>## 
## Call:
## preProcess.default(x = X)
## 
## Created from 11776 samples and 52 variables
## Pre-processing: centered, scaled
</code></pre>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">XCS</span> <span class="pl-k">&lt;-</span> predict(<span class="pl-smi">preProc</span>, <span class="pl-smi">X</span>)
<span class="pl-smi">DTrainCS</span> <span class="pl-k">&lt;-</span> data.table(<span class="pl-k">data.frame</span>(<span class="pl-v">classe</span> <span class="pl-k">=</span> <span class="pl-smi">DTrain</span>[, <span class="pl-smi">classe</span>], <span class="pl-smi">XCS</span>))</pre></div>

<p>Apply the centering and scaling to the probing dataset.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">X</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">DProbe</span>[, <span class="pl-smi">predCandidates</span>, <span class="pl-v">with</span><span class="pl-k">=</span><span class="pl-c1">FALSE</span>]
<span class="pl-smi">XCS</span> <span class="pl-k">&lt;-</span> predict(<span class="pl-smi">preProc</span>, <span class="pl-smi">X</span>)
<span class="pl-smi">DProbeCS</span> <span class="pl-k">&lt;-</span> data.table(<span class="pl-k">data.frame</span>(<span class="pl-v">classe</span> <span class="pl-k">=</span> <span class="pl-smi">DProbe</span>[, <span class="pl-smi">classe</span>], <span class="pl-smi">XCS</span>))</pre></div>

<p>Check for near zero variance.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">nzv</span> <span class="pl-k">&lt;-</span> nearZeroVar(<span class="pl-smi">DTrainCS</span>, <span class="pl-v">saveMetrics</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>)
<span class="pl-k">if</span> (any(<span class="pl-smi">nzv</span><span class="pl-k">$</span><span class="pl-smi">nzv</span>)) <span class="pl-smi">nzv</span> <span class="pl-k">else</span> message(<span class="pl-s"><span class="pl-pds">"</span>No variables with near zero variance<span class="pl-pds">"</span></span>)</pre></div>

<pre><code>## No variables with near zero variance
</code></pre>

<p>Examine groups of prediction variables.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-en">histGroup</span> <span class="pl-k">&lt;-</span> <span class="pl-k">function</span> (<span class="pl-smi">data</span>, <span class="pl-smi">regex</span>) {
  <span class="pl-smi">col</span> <span class="pl-k">&lt;-</span> grep(<span class="pl-smi">regex</span>, names(<span class="pl-smi">data</span>))
  <span class="pl-smi">col</span> <span class="pl-k">&lt;-</span> c(<span class="pl-smi">col</span>, which(names(<span class="pl-smi">data</span>) <span class="pl-k">==</span> <span class="pl-s"><span class="pl-pds">"</span>classe<span class="pl-pds">"</span></span>))
  library(<span class="pl-smi">reshape2</span>)
  <span class="pl-smi">n</span> <span class="pl-k">&lt;-</span> nrow(<span class="pl-smi">data</span>)
  <span class="pl-smi">DMelted</span> <span class="pl-k">&lt;-</span> melt(<span class="pl-smi">data</span>[, <span class="pl-smi">col</span>, <span class="pl-v">with</span><span class="pl-k">=</span><span class="pl-c1">FALSE</span>][, <span class="pl-smi">rownum</span> <span class="pl-k">:</span><span class="pl-k">=</span> seq(<span class="pl-c1">1</span>, <span class="pl-smi">n</span>)], <span class="pl-v">id.vars</span><span class="pl-k">=</span>c(<span class="pl-s"><span class="pl-pds">"</span>rownum<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>classe<span class="pl-pds">"</span></span>))
  library(<span class="pl-smi">ggplot2</span>)
  ggplot(<span class="pl-smi">DMelted</span>, aes(<span class="pl-v">x</span><span class="pl-k">=</span><span class="pl-smi">classe</span>, <span class="pl-v">y</span><span class="pl-k">=</span><span class="pl-smi">value</span>)) <span class="pl-k">+</span>
    geom_violin(aes(<span class="pl-v">color</span><span class="pl-k">=</span><span class="pl-smi">classe</span>, <span class="pl-v">fill</span><span class="pl-k">=</span><span class="pl-smi">classe</span>), <span class="pl-v">alpha</span><span class="pl-k">=</span><span class="pl-c1">1</span><span class="pl-k">/</span><span class="pl-c1">2</span>) <span class="pl-k">+</span>
<span class="pl-c">#     geom_jitter(aes(color=classe, fill=classe), alpha=1/10) +</span>
<span class="pl-c">#     geom_smooth(aes(group=1), method="gam", color="black", alpha=1/2, size=2) +</span>
    facet_wrap(<span class="pl-k">~</span> <span class="pl-smi">variable</span>, <span class="pl-v">scale</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>free_y<span class="pl-pds">"</span></span>) <span class="pl-k">+</span>
    scale_color_brewer(<span class="pl-v">palette</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Spectral<span class="pl-pds">"</span></span>) <span class="pl-k">+</span>
    scale_fill_brewer(<span class="pl-v">palette</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>Spectral<span class="pl-pds">"</span></span>) <span class="pl-k">+</span>
    labs(<span class="pl-v">x</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>, <span class="pl-v">y</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>) <span class="pl-k">+</span>
    theme(<span class="pl-v">legend.position</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>none<span class="pl-pds">"</span></span>)
}
histGroup(<span class="pl-smi">DTrainCS</span>, <span class="pl-s"><span class="pl-pds">"</span>belt<span class="pl-pds">"</span></span>)</pre></div>

<pre><code>## Warning: package 'reshape2' was built under R version 3.0.3
</code></pre>

<p><a href="/Emaasit/MachineLearning/blob/master/predictionAssignment_files/figure-html/histGroup-1.png" target="_blank"><img src="/Emaasit/MachineLearning/raw/master/predictionAssignment_files/figure-html/histGroup-1.png" alt="" style="max-width:100%;"></a> </p>

<div class="highlight highlight-source-r"><pre>histGroup(<span class="pl-smi">DTrainCS</span>, <span class="pl-s"><span class="pl-pds">"</span>[^(fore)]arm<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/Emaasit/MachineLearning/blob/master/predictionAssignment_files/figure-html/histGroup-2.png" target="_blank"><img src="/Emaasit/MachineLearning/raw/master/predictionAssignment_files/figure-html/histGroup-2.png" alt="" style="max-width:100%;"></a> </p>

<div class="highlight highlight-source-r"><pre>histGroup(<span class="pl-smi">DTrainCS</span>, <span class="pl-s"><span class="pl-pds">"</span>dumbbell<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/Emaasit/MachineLearning/blob/master/predictionAssignment_files/figure-html/histGroup-3.png" target="_blank"><img src="/Emaasit/MachineLearning/raw/master/predictionAssignment_files/figure-html/histGroup-3.png" alt="" style="max-width:100%;"></a> </p>

<div class="highlight highlight-source-r"><pre>histGroup(<span class="pl-smi">DTrainCS</span>, <span class="pl-s"><span class="pl-pds">"</span>forearm<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/Emaasit/MachineLearning/blob/master/predictionAssignment_files/figure-html/histGroup-4.png" target="_blank"><img src="/Emaasit/MachineLearning/raw/master/predictionAssignment_files/figure-html/histGroup-4.png" alt="" style="max-width:100%;"></a> </p>

<h1><a id="user-content-train-a-prediction-model" class="anchor" href="#train-a-prediction-model" aria-hidden="true"><span class="octicon octicon-link"></span></a>Train a prediction model</h1>

<p>Using random forest, the out of sample error should be small.
The error will be estimated using the 40% probing sample.
I would be quite happy with an error estimate of 3% or less.</p>

<p>Set up the parallel clusters.</p>

<div class="highlight highlight-source-r"><pre>library(<span class="pl-smi">parallel</span>)
library(<span class="pl-smi">doParallel</span>)</pre></div>

<pre><code>## Warning: package 'doParallel' was built under R version 3.0.3
</code></pre>

<pre><code>## Loading required package: foreach
</code></pre>

<pre><code>## Warning: package 'foreach' was built under R version 3.0.3
</code></pre>

<pre><code>## Loading required package: iterators
</code></pre>

<pre><code>## Warning: package 'iterators' was built under R version 3.0.3
</code></pre>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">cl</span> <span class="pl-k">&lt;-</span> makeCluster(detectCores() <span class="pl-k">-</span> <span class="pl-c1">1</span>)
registerDoParallel(<span class="pl-smi">cl</span>)</pre></div>

<p>Set the control parameters.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">ctrl</span> <span class="pl-k">&lt;-</span> trainControl(<span class="pl-v">classProbs</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>,
                     <span class="pl-v">savePredictions</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>,
                     <span class="pl-v">allowParallel</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>)</pre></div>

<p>Fit model over the tuning parameters.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">method</span> <span class="pl-k">&lt;-</span> <span class="pl-s"><span class="pl-pds">"</span>rf<span class="pl-pds">"</span></span>
system.time(<span class="pl-smi">trainingModel</span> <span class="pl-k">&lt;-</span> train(<span class="pl-smi">classe</span> <span class="pl-k">~</span> ., <span class="pl-v">data</span><span class="pl-k">=</span><span class="pl-smi">DTrainCS</span>, <span class="pl-v">method</span><span class="pl-k">=</span><span class="pl-smi">method</span>))</pre></div>

<pre><code>## Loading required package: randomForest
</code></pre>

<pre><code>## Warning: package 'randomForest' was built under R version 3.0.3
</code></pre>

<pre><code>## randomForest 4.6-10
## Type rfNews() to see new features/changes/bug fixes.
## Loading required namespace: e1071
</code></pre>

<pre><code>##    user  system elapsed 
##   46.86    0.39 1102.53
</code></pre>

<p>Stop the clusters.</p>

<div class="highlight highlight-source-r"><pre>stopCluster(<span class="pl-smi">cl</span>)</pre></div>

<h2><a id="user-content-evaluate-the-model-on-the-training-dataset" class="anchor" href="#evaluate-the-model-on-the-training-dataset" aria-hidden="true"><span class="octicon octicon-link"></span></a>Evaluate the model on the training dataset</h2>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">trainingModel</span></pre></div>

<pre><code>## Random Forest 
## 
## 11776 samples
##    52 predictor
##     5 classes: 'A', 'B', 'C', 'D', 'E' 
## 
## No pre-processing
## Resampling: Bootstrapped (25 reps) 
## 
## Summary of sample sizes: 11776, 11776, 11776, 11776, 11776, 11776, ... 
## 
## Resampling results across tuning parameters:
## 
##   mtry  Accuracy  Kappa  Accuracy SD  Kappa SD
##    2    0.986     0.982  0.00163      0.00206 
##   27    0.987     0.984  0.00158      0.00200 
##   52    0.977     0.971  0.00438      0.00555 
## 
## Accuracy was used to select the optimal model using  the largest value.
## The final value used for the model was mtry = 27.
</code></pre>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">hat</span> <span class="pl-k">&lt;-</span> predict(<span class="pl-smi">trainingModel</span>, <span class="pl-smi">DTrainCS</span>)
confusionMatrix(<span class="pl-smi">hat</span>, <span class="pl-smi">DTrain</span>[, <span class="pl-smi">classe</span>])</pre></div>

<pre><code>## Confusion Matrix and Statistics
## 
##           Reference
## Prediction    A    B    C    D    E
##          A 3348    0    0    0    0
##          B    0 2279    0    0    0
##          C    0    0 2054    0    0
##          D    0    0    0 1930    0
##          E    0    0    0    0 2165
## 
## Overall Statistics
##                                      
##                Accuracy : 1          
##                  95% CI : (0.9997, 1)
##     No Information Rate : 0.2843     
##     P-Value [Acc &gt; NIR] : &lt; 2.2e-16  
##                                      
##                   Kappa : 1          
##  Mcnemar's Test P-Value : NA         
## 
## Statistics by Class:
## 
##                      Class: A Class: B Class: C Class: D Class: E
## Sensitivity            1.0000   1.0000   1.0000   1.0000   1.0000
## Specificity            1.0000   1.0000   1.0000   1.0000   1.0000
## Pos Pred Value         1.0000   1.0000   1.0000   1.0000   1.0000
## Neg Pred Value         1.0000   1.0000   1.0000   1.0000   1.0000
## Prevalence             0.2843   0.1935   0.1744   0.1639   0.1838
## Detection Rate         0.2843   0.1935   0.1744   0.1639   0.1838
## Detection Prevalence   0.2843   0.1935   0.1744   0.1639   0.1838
## Balanced Accuracy      1.0000   1.0000   1.0000   1.0000   1.0000
</code></pre>

<h2><a id="user-content-evaluate-the-model-on-the-probing-dataset" class="anchor" href="#evaluate-the-model-on-the-probing-dataset" aria-hidden="true"><span class="octicon octicon-link"></span></a>Evaluate the model on the probing dataset</h2>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">hat</span> <span class="pl-k">&lt;-</span> predict(<span class="pl-smi">trainingModel</span>, <span class="pl-smi">DProbeCS</span>)
confusionMatrix(<span class="pl-smi">hat</span>, <span class="pl-smi">DProbeCS</span>[, <span class="pl-smi">classe</span>])</pre></div>

<pre><code>## Confusion Matrix and Statistics
## 
##           Reference
## Prediction    A    B    C    D    E
##          A 2230   16    0    0    0
##          B    1 1498    6    2    2
##          C    0    4 1353   18    7
##          D    0    0    9 1265    7
##          E    1    0    0    1 1426
## 
## Overall Statistics
##                                           
##                Accuracy : 0.9906          
##                  95% CI : (0.9882, 0.9926)
##     No Information Rate : 0.2845          
##     P-Value [Acc &gt; NIR] : &lt; 2.2e-16       
##                                           
##                   Kappa : 0.9881          
##  Mcnemar's Test P-Value : NA              
## 
## Statistics by Class:
## 
##                      Class: A Class: B Class: C Class: D Class: E
## Sensitivity            0.9991   0.9868   0.9890   0.9837   0.9889
## Specificity            0.9971   0.9983   0.9955   0.9976   0.9997
## Pos Pred Value         0.9929   0.9927   0.9790   0.9875   0.9986
## Neg Pred Value         0.9996   0.9968   0.9977   0.9968   0.9975
## Prevalence             0.2845   0.1935   0.1744   0.1639   0.1838
## Detection Rate         0.2842   0.1909   0.1724   0.1612   0.1817
## Detection Prevalence   0.2863   0.1923   0.1761   0.1633   0.1820
## Balanced Accuracy      0.9981   0.9925   0.9923   0.9906   0.9943
</code></pre>

<h2><a id="user-content-display-the-final-model" class="anchor" href="#display-the-final-model" aria-hidden="true"><span class="octicon octicon-link"></span></a>Display the final model</h2>

<div class="highlight highlight-source-r"><pre>varImp(<span class="pl-smi">trainingModel</span>)</pre></div>

<pre><code>## rf variable importance
## 
##   only 20 most important variables shown (out of 52)
## 
##                      Overall
## roll_belt            100.000
## pitch_forearm         59.809
## yaw_belt              54.351
## pitch_belt            45.919
## magnet_dumbbell_z     43.763
## roll_forearm          43.518
## magnet_dumbbell_y     43.318
## accel_dumbbell_y      22.405
## roll_dumbbell         18.299
## magnet_dumbbell_x     17.987
## accel_forearm_x       17.502
## accel_belt_z          14.588
## magnet_belt_z         14.427
## accel_dumbbell_z      13.935
## magnet_forearm_z      13.907
## total_accel_dumbbell  13.199
## magnet_belt_y         12.330
## yaw_arm               11.810
## gyros_belt_z          11.176
## magnet_belt_x          9.191
</code></pre>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">trainingModel</span><span class="pl-k">$</span><span class="pl-smi">finalModel</span></pre></div>

<pre><code>## 
## Call:
##  randomForest(x = x, y = y, mtry = param$mtry) 
##                Type of random forest: classification
##                      Number of trees: 500
## No. of variables tried at each split: 27
## 
##         OOB estimate of  error rate: 0.79%
## Confusion matrix:
##      A    B    C    D    E class.error
## A 3341    5    2    0    0 0.002090800
## B   16 2255    7    1    0 0.010530935
## C    0   10 2037    7    0 0.008276534
## D    0    1   27 1899    3 0.016062176
## E    1    2    2    9 2151 0.006466513
</code></pre>

<p><strong>The estimated error rate is less than 1%.</strong></p>

<p>Save training model object for later.</p>

<div class="highlight highlight-source-r"><pre>save(<span class="pl-smi">trainingModel</span>, <span class="pl-v">file</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>trainingModel.RData<span class="pl-pds">"</span></span>)</pre></div>

<h1><a id="user-content-predict-on-the-test-data" class="anchor" href="#predict-on-the-test-data" aria-hidden="true"><span class="octicon octicon-link"></span></a>Predict on the test data</h1>

<p>Load the training model.</p>

<div class="highlight highlight-source-r"><pre>load(<span class="pl-v">file</span><span class="pl-k">=</span><span class="pl-s"><span class="pl-pds">"</span>trainingModel.RData<span class="pl-pds">"</span></span>, <span class="pl-v">verbose</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>)</pre></div>

<pre><code>## Loading objects:
##   trainingModel
</code></pre>

<p>Get predictions and evaluate.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-smi">DTestCS</span> <span class="pl-k">&lt;-</span> predict(<span class="pl-smi">preProc</span>, <span class="pl-smi">DTest</span>[, <span class="pl-smi">predCandidates</span>, <span class="pl-v">with</span><span class="pl-k">=</span><span class="pl-c1">FALSE</span>])
<span class="pl-smi">hat</span> <span class="pl-k">&lt;-</span> predict(<span class="pl-smi">trainingModel</span>, <span class="pl-smi">DTestCS</span>)
<span class="pl-smi">DTest</span> <span class="pl-k">&lt;-</span> cbind(<span class="pl-smi">hat</span> , <span class="pl-smi">DTest</span>)
subset(<span class="pl-smi">DTest</span>, <span class="pl-v">select</span><span class="pl-k">=</span>names(<span class="pl-smi">DTest</span>)[grep(<span class="pl-s"><span class="pl-pds">"</span>belt|[^(fore)]arm|dumbbell|forearm<span class="pl-pds">"</span></span>, names(<span class="pl-smi">DTest</span>), <span class="pl-v">invert</span><span class="pl-k">=</span><span class="pl-c1">TRUE</span>)])</pre></div>

<pre><code>##     hat V1 user_name raw_timestamp_part_1 raw_timestamp_part_2
##  1:   B  1     pedro           1323095002               868349
##  2:   A  2    jeremy           1322673067               778725
##  3:   B  3    jeremy           1322673075               342967
##  4:   A  4    adelmo           1322832789               560311
##  5:   A  5    eurico           1322489635               814776
##  6:   E  6    jeremy           1322673149               510661
##  7:   D  7    jeremy           1322673128               766645
##  8:   B  8    jeremy           1322673076                54671
##  9:   A  9  carlitos           1323084240               916313
## 10:   A 10   charles           1322837822               384285
## 11:   B 11  carlitos           1323084277                36553
## 12:   C 12    jeremy           1322673101               442731
## 13:   B 13    eurico           1322489661               298656
## 14:   A 14    jeremy           1322673043               178652
## 15:   E 15    jeremy           1322673156               550750
## 16:   E 16    eurico           1322489713               706637
## 17:   A 17     pedro           1323094971               920315
## 18:   B 18  carlitos           1323084285               176314
## 19:   B 19     pedro           1323094999               828379
## 20:   B 20    eurico           1322489658               106658
##       cvtd_timestamp new_window num_window problem_id
##  1: 05/12/2011 14:23         no         74          1
##  2: 30/11/2011 17:11         no        431          2
##  3: 30/11/2011 17:11         no        439          3
##  4: 02/12/2011 13:33         no        194          4
##  5: 28/11/2011 14:13         no        235          5
##  6: 30/11/2011 17:12         no        504          6
##  7: 30/11/2011 17:12         no        485          7
##  8: 30/11/2011 17:11         no        440          8
##  9: 05/12/2011 11:24         no        323          9
## 10: 02/12/2011 14:57         no        664         10
## 11: 05/12/2011 11:24         no        859         11
## 12: 30/11/2011 17:11         no        461         12
## 13: 28/11/2011 14:14         no        257         13
## 14: 30/11/2011 17:10         no        408         14
## 15: 30/11/2011 17:12         no        779         15
## 16: 28/11/2011 14:15         no        302         16
## 17: 05/12/2011 14:22         no         48         17
## 18: 05/12/2011 11:24         no        361         18
## 19: 05/12/2011 14:23         no         72         19
## 20: 28/11/2011 14:14         no        255         20
</code></pre>

<h2><a id="user-content-submission-to-coursera" class="anchor" href="#submission-to-coursera" aria-hidden="true"><span class="octicon octicon-link"></span></a>Submission to Coursera</h2>

<p>Write submission files to <code>predictionAssignment_files/answers</code>.</p>

<div class="highlight highlight-source-r"><pre><span class="pl-v">pml_write_files</span> <span class="pl-k">=</span> <span class="pl-k">function</span>(<span class="pl-smi">x</span>){
  <span class="pl-v">n</span> <span class="pl-k">=</span> length(<span class="pl-smi">x</span>)
  <span class="pl-smi">path</span> <span class="pl-k">&lt;-</span> <span class="pl-s"><span class="pl-pds">"</span>predictionAssignment_files/answers<span class="pl-pds">"</span></span>
  <span class="pl-k">for</span>(<span class="pl-smi">i</span> <span class="pl-k">in</span> <span class="pl-c1">1</span><span class="pl-k">:</span><span class="pl-smi">n</span>){
    <span class="pl-v">filename</span> <span class="pl-k">=</span> paste0(<span class="pl-s"><span class="pl-pds">"</span>problem_id_<span class="pl-pds">"</span></span>,<span class="pl-smi">i</span>,<span class="pl-s"><span class="pl-pds">"</span>.txt<span class="pl-pds">"</span></span>)
    write.table(<span class="pl-smi">x</span>[<span class="pl-smi">i</span>],<span class="pl-v">file</span><span class="pl-k">=</span>file.path(<span class="pl-smi">path</span>, <span class="pl-smi">filename</span>),<span class="pl-v">quote</span><span class="pl-k">=</span><span class="pl-c1">FALSE</span>,<span class="pl-v">row.names</span><span class="pl-k">=</span><span class="pl-c1">FALSE</span>,<span class="pl-v">col.names</span><span class="pl-k">=</span><span class="pl-c1">FALSE</span>)
  }
}
pml_write_files(<span class="pl-smi">hat</span>)</pre></div>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <!-- </textarea> --><!-- '"` --><form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

  </div>
  <div class="modal-backdrop"></div>
</div>

    </div>
  </div>

    </div>

        <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>
        <li><a href="https://github.com/pricing" data-ga-click="Footer, go to pricing, text:pricing">Pricing</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github " title="GitHub "></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.06986s from github-fe142-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
        <li><a href="https://help.github.com" data-ga-click="Footer, go to help, text:help">Help</a></li>
    </ul>
  </div>
</div>



    
    
    

    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <button type="button" class="flash-close js-flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
        <span class="octicon octicon-x"></span>
      </button>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" integrity="sha256-7460qJ7p88i3YTMH/liaj1cFgX987ie+xRzl6WMjSr8=" src="https://assets-cdn.github.com/assets/frameworks-ef8eb4a89ee9f3c8b7613307fe589a8f5705817f7cee27bec51ce5e963234abf.js"></script>
      <script async="async" crossorigin="anonymous" integrity="sha256-S2uOfRHrt7zoUSbTtBMMgAQfKubV1u+JAajAw/fLgNI=" src="https://assets-cdn.github.com/assets/github-4b6b8e7d11ebb7bce85126d3b4130c80041f2ae6d5d6ef8901a8c0c3f7cb80d2.js"></script>
      
      
      
    <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner hidden">
      <span class="octicon octicon-alert"></span>
      <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
      <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
    </div>
  </body>
</html>

