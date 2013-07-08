## About

Holds Redu external courses' pages. It's a fork of [Redu's courses starter kit](https://github.com/redu/courses-starter-kit).

### Dependencies

- Ruby 2
- Bundler
- [Middleman](https://github.com/middleman/middleman)
- [Redu's UI Components](http://developers.redu.com.br/ui-components)

![snapshot](https://doc-14-0o-docs.googleusercontent.com/docs/securesc/c8q50lp7palrgn6tkprt6op63l9vhrea/0njrpcbcu65b0i4pjmshm2sffilqtgl9/1372788000000/17128520968404989744/17128520968404989744/0BzNrLdHF4h5bX2diOTRZQXZTclk?h=16653014193614665626&e=download)

## Setup

```sh
$ bundle install
$ bundle exec middleman
```

Visit http://0.0.0.0:4567

### Configuration

You can customize some configurations editing config.rb file:

```ruby
# Course name
# Course name
set :course_name, "Course name"

# Contact email shown at contact modal
set :contact_email, "example@example.com"

# URL opened from a <iframe> within contact modal. contact_mail is showed whenever contact_url is nil.
set :contact_url, "http://example.com/contacts/new?course=#{config.course_name}"
```

## What need to be done?

- Make layout responsive
- Link contact form
- Make it simple to embed payment gateway endpoint

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request


<img src="https://github.com/downloads/redu/redupy/redutech-marca.png" alt="Redu Educational Technologies" width="300">

This project is maintained and funded by [Redu Educational Techologies](http://tech.redu.com.br).

## Copyright

Copyright (c) 2013 Redu Educational Technologies

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
