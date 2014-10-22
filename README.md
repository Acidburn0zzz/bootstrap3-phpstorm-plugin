Bootstrap 3 WebStorm/PHPStorm Plugin
====================================

A WebStorm/PHPStorm plugin containing Bootstrap 3 live templates - lots of live template!

![Plugin in action](animation.gif)

Feel free to let me know what else you want added via:

- Twitter [@JasonMortonNZ](https://twitter.com/jasonmortonnz)
- The [Issues](https://github.com/JasonMortonNZ/bootstrap3-phpstorm-plugin/issues) section on GitHub


### Intallation (in three easy steps)

To install the plugin open your editor (WebStorm or PHPStorm) and hit:

1) `File > Settings > Plugins` and click on the `Browse repositories` button.

2) Search for `Bootstrap` then right click and select `Download plugin`.

3) Finally hit the `Apply` button, agree to restart your IDE and you're all done!


## What's included - contents
- [CDN](#cdn)
- [Templates](#templates)
- [Forms](#forms)
- [Tables](#tables)
- [Input](#input-fields-form-fields)
- [Alerts](#alerts)
- [Badges](#badges)
- [Breadcrumbs](#breadcrumbs)
- [Buttons](#buttons)
- [Grid](#grid)
- [Images](#images)
- [Icons](#icons)
- [Labels](#labels)
- [Pagination](#pagination)
- [Navigation](#navigation)
- [Panels](#panels)
- [List Groups](#list-groups)
- [Media Objects](#media-objects)
- [Icons](#icons)
- [Clearfix](#clearfix)
- [License](#license)

### CDN

| Component                      | Snippet code                   |
|------------------------------- | :-----------------------------:|
| CDN link (both CSS & JS)       | bs3-cdn                        |
| CDN link (CSS only)            | bs3-cdn:css                    |
| CDN link (JS only)             | bs3-cdn:js                     |

### Templates

| Component                      | Snippet code                   |
|------------------------------- | :-----------------------------:|
| HTML5 Template Layout          | bs3-template:html5             |

### Forms

| Component                      | Snippet code                   |
|------------------------------- | :-----------------------------:|
| Form                           | bs3-form                       |
| Inline Form                    | bs3-form:inline                |
| Horizontal Form                | bs3-form:horizontal            |

### Tables

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Table                          | bs3-table                      |
| Bordered Table                 | bs3-table:bordered             |
| Condensed Table                | bs3-table:condensed            |
| Hover Table                    | bs3-table:hover                |
| Striped Table                  | bs3-table:striped              |

### Input Fields (Form fields)

#### Currently Working

| Component                      | Snippet code                   | Options |
|------------------------------- | :----------------------------: | :-----: |
| Text Input                     | bs3-input                      | :h      |
| Select Input                   | bs3-select                     |         |
| Checkbox                       | bs3-checkbox                   |         |
| Radio                          | bs3-radio                      | :h      |
| Submit                         | bs3-submit                     | :h      |

#### Coming Soon

**Note:** you can add " :h " to the end of any input field snippet to make it compatible with Bootstrap 3 horizontal forms. **E.g.**
- bs3-input:text:h
- bs3-input:hidden:h

| Component                      | Snippet code                   | Options |
|------------------------------- | :----------------------------: | :-----: |
| Label                          | bs3-input:label                |         |
| Text Input                     | bs3-input:text                 | :h      |
| Email Input                    | bs3-input:email                | :h      |
| Password Input                 | bs3-input:password             | :h      |
| Hidden Input                   | bs3-input:hidden               | :h      |
| Url Input                      | bs3-input:url                  | :h      |
| Color Input                    | bs3-input:color                | :h      |
| Number Input                   | bs3-input:number               | :h      |
| Range Input                    | bs3-input:range                | :h      |
| Date Input                     | bs3-input:date                 | :h      |
| Week Input                     | bs3-input:week                 | :h      |
| Month Input                    | bs3-input:month                | :h      |
| Time Input                     | bs3-input:time                 | :h      |
| Tel Input                      | bs3-input:tel                  | :h      |
| Search Input                   | bs3-input:search               | :h      |
| Reset Input                    | bs3-input:reset                | :h      |
| Submit Input                   | bs3-input:submit               | :h      |
| Checkbox Input                 | bs3-input:checkbox             | :h      |
| Radio Box Input                | bs3-input:radio                | :h      |
| Textarea                       | bs3-textarea                   | :h      |

### Alerts

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Alert Box (Default)            | bs3-alert                      |
| Danger Alert Box               | bs3-alert:danger               |
| Info Alert Box                 | bs3-alert:info                 |
| Success Alert Box              | bs3-alert:success              |
| Warning Alert Box              | bs3-alert:warning              |

### Badges

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Badge (Default)                | bs3-badge                      |

### Breadcrumbs

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Breadcrumbs                    | bs3-breadcrumbs                |

### Buttons
#### Buttons COMING SOON

**Note:** all button snippets below can have any of the following options append to the end of the snippet *.
- :danger
- :default
- :disabled
- :info
- :primary
- :success
- :warning

**An example:**
- bs3-button:success
- bs3-large-button:disabled
- bs3-block-button:warning

| Component                      | Snippet code                   | Options |
|------------------------------- | :----------------------------: | :-----: |
| Button                         | bs3-button                     |  *      |
| Block Button                   | bs3-block-button               |  *      |
| Mini Button                    | bs3-xs-button                  |  *      |
| Small Button                   | bs3-sm-button                  |  *      |
| Large Button                   | bs3-lg-button                  |  *      |

### Grid

**Note:** The bs3-col snippet can be used both on its own or with the addition of a colon followed by the number of columns required: **E.g.**

- bs3-col
- bs3-col:6
- bs3-col:12

| Component                      | Snippet code                   | Options |
|------------------------------- | :----------------------------: | :-----: |
| Column                         | bs3-col                        | :1-12   |
| Row                            | bs3-row                        |         |
| Container                      | bs3-container                  |         |

### Icons

| Component                      | Snippet code                   |
|------------------------------- | :-----------------------------:|
| Glyphicon                      | bs3-icon:glyphicon             |
| Icon (Font Awesome)            | bs3-icon                       |

### Images

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Thumbnail                      | bs3-thumbnail                  |
| Thumbnail with content         | bs3-thumbnail:content          |

### Labels

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Label                          | bs3-label                      |
| Danger Label                   | bs3-label:danger               |
| Info Label                     | bs3-label:info                 |
| Success Label                  | bs3-label:success              |
| Warning Label                  | bs3-label:warning              |

### Pagination

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Pager                          | bs3-pager                      |
| Aligned Pager                  | bs3-pager:aligned              |
| Pagination                     | bs3-pagination                 |
| Pagination:small               | bs3-pagination:small           |
| Pagination:large               | bs3-pagination:large           |

### Navigation

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Navbar (basic navbar)          | bs3-navbar                     |
| Navbar Brand Element           | bs3-navbar:brand               |
| Navbar Button                  | bs3-navbar:button              |
| Navbar Form                    | bs3-navbar:form                |
| Navbar Link                    | bs3-navbar:link                |
| Navbar Text                    | bs3-navbar:text                |
| Navbar Fixed-Botton            | bs3-navbar:fixed-bottom        |
| Navbar Fixed-Top               | bs3-navbar:fixed-top           |
| Navbar Inverse                 | bs3-navbar:inverse             |
| Navbar Responsive              | bs3-navbar:responsive          |
| Navbar Static-Top              | bs3-navbar:static-top          |

### Jumbotron

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Jumbotron (ex Hero Unit)       | bs3-jumbotron                  |

### Panels

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Panel                          | bs3-panel                      |
| Panel (contextual)             | bs3-panel:{warning,success,info,danger,primary}                  |
| Panel (with heading)           | bs3-panel:heading              |
| Panel (with footer)            | bs3-panel:footer               |

### List-groups

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| List group                     | bs3-list-group                 |
| List group (with badges)       | bs3-list-group:badges          |
| List group (linked list)       | bs3-list-group:linked          |
| List group (with content)      | bs3-list-group:content         |

### Media Objects

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Media Object                   | bs3-media-object               |

### Clearfix

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------: |
| Clearfix                       | bs3-clearfix                   |

### License

Bootstrap 3 - PHPStorm Plugin is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
