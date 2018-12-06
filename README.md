# learn-mackerel-behavior

## Usage

1. install `docker` and `docker-compose`
1. clone this repository and into the directory

    ```bash
    $ git clone https://github.com/ryosms/learn-mackerel-behavior
    $ cd learn-mackerel-behavior
    ```

1. setup environment

    ```bash
    $ cp sample.env .env
    $ vi .env
    edit according to your environment
    ```

1. create docker-compose project

    ```bash
    $ docker-compose up --no-start
    ```

1. start an any service and check diff(ex: `standard`)

    ```bash
    $ docker-compose start standard
    $ git diff
    ```
