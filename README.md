Nest Dashing Widget 
===================

Nest widget for [Dashing](http://shopify.github.com/dashing)
 
## Preview 
![](https://dl.dropboxusercontent.com/u/2138838/Github/nest_widget/screen_1.png)
![](https://dl.dropboxusercontent.com/u/2138838/Github/nest_widget/screen_2.png) 
 
## Dependencies

Add the `nest_thermostat` to the Gemfile of your Dashing dashboard:

```ruby
gem 'nest_thermostat'
```

and run `bundle install`.

## Installation

To login to your nest account setup both the `NEST_USER` and `NEST_PASSWORD` environment variables

## Usage

To use this widget, copy `nest.coffee`, `nest.html` and `nest.scss` into the `/widgets/nest` directory of your dashboard. Copy `nest_logo.png` and `nest_leaf.png` into the `/assets/images` directory and put the `nest.rb` file in your `/jobs` folder.

To include the widget on your dashboard, add the following snippet to the dashboard layout file:

```ruby
  <li data-row="1" data-col="1" data-sizex="1" data-sizey="1">
      <div data-id="nest" data-view="Nest" data-title="Nest Temp"></div>
  </li>  
```
