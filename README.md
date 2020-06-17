# rtl2mqtt with Dockerfile

## Environment Variables

| Name            | Description                                                                                                         |
| --------------- | ------------------------------------------------------------------------------------------------------------------- |
| AMQP_SERVER     | The URL must be in the form:<br>**amqp(s)://[username[:password]@]host[:port]\(/vhost)**<br>without a tailing slash |
| AMQP_EXCHANGE   | The Exchange to publish to                                                                                          |
| AMQP_ROUTINGKEY | The RoutingKey that should be set on publish                                                                        |
| TZ              | Timezone, like "Europe/Berlin"                                                                                      |
