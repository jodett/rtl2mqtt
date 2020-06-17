# rtl2mqtt with Dockerfile

## Environment Variables

| Name            | Description                                                              |
| --------------- | ------------------------------------------------------------------------ |
| AMQP_SERVER     | The URL must be in the form: amqp(s)://[username[:password]@]host[:port] |
| AMQP_EXCHANGE   | The Exchange to publish to                                               |
| AMQP_ROUTINGKEY | The RoutingKey that should be set on publish                             |
| TZ              | Timezone, like "Europe/Berlin"                                           |
