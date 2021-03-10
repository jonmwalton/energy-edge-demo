Used sonatype to find the packages on maven central 

download and create a folder structure

download the qpid amqp jms client from access.redhat.com and copy the jar file into the camel-amqp-kafka-connector-folder (not copied into the repo)

camelkakfatest/connectors and deployed the connector or connectors there

run

oc start-build energy-connect-s2i-cluster-connect --from-dir ./camelkafkatest/connectors/ --follow

create kafka connector using the yaml file in the config directory