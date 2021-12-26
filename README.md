# [genicsblog.com](https://genicsblog.com)

Static site for genicsblog.com

## Local setup

### Prerequisites

Should have installed [ruby](https://www.ruby-lang.org) and [Node.js](https://nodejs.org) before proceeding. Install `jekyll` and `bundler` with:

```
gem install bundler jekyll
```

### Steps

- Clone the repository and cd
    ```shell
    git clone https://github.com/genicsblog/genicsblog.github.io.git
    cd genicsblog
    ```

- Install dependencies
    ```shell
    bundle install
    npm install
    ```

- Run the static site on localhost
    ```shell
    bundle exec jekyll serve
    ```

    If you get an error with file permissions, try:
    ```shell
    rake serve
    ```