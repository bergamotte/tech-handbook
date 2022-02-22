# Tech stack

- We use the [Ruby on Rails](https://rubyonrails.org/) framework.
- We use [Postgresql](https://www.postgresql.org/), [Redis](https://redis.io/) and [ElasticSearch](https://www.elastic.co/) for our data needs.
- We render HTML pages server side from Rails.
- We provide client side dynamic behavior with [Stimulus](https://stimulus.hotwired.dev/), [Turbo Frames](https://turbo.hotwired.dev/handbook/frames) and [Streams](https://turbo.hotwired.dev/handbook/streams) for partial updates.
- Our write modern JavaScript that is transpiled with [Babel](https://babeljs.io/) and [Webpack](https://webpack.js.org/).
- Our design system lives in [Figma](https://www.figma.com/), and we style in [Sass](https://sass-lang.com/) (scss format).
- We test with [RSpec](https://rspec.info/), [Capybara](http://teamcapybara.github.io/capybara/) and [FactoryBot](https://github.com/thoughtbot/factory_bot).

# Helper tools

- We monitor our systems with [Datadog](https://www.datadoghq.com/).
- We notify issues via [Sentry](https://sentry.io/welcome/).
- We use [CodeBuild](https://aws.amazon.com/codebuild/) and other AWS tools for Continuous Integration and deployment of feature/review environments.
- [Rubocop](https://rubocop.org/), [Eslint](https://eslint.org/) and [Stylelint](https://stylelint.io/) help us improve the quality of our software.
- We heavily use Github Projects, Issues, Discussions and Pull Request Reviews.
- We are proponents of async, distributed work. Async communication happens in Github or email.
- Real time communication happens in [Slack](https://slack.com/), Google [Meeet](https://meet.google.com/) or [Zoom](https://zoom.us/).

# Architecture

- We host our codebase in a [monorepo](https://en.wikipedia.org/wiki/Monorepo).
- We [modularize](https://www.modularrails.com/) our monolith with Rails Engines, Gems and Services.
- We strive for bounded contexts with small surface areas and separation of concerns.

---

Continue to [How we work](how_we_work.md)
