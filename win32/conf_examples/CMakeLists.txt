#
# clamav config files
#

install(
    FILES
        ${CMAKE_CURRENT_SOURCE_DIR}/clamd.conf.sample
    DESTINATION
        ${APP_CONFIG_DIRECTORY}/conf_examples)

install(
    FILES
        ${CMAKE_CURRENT_SOURCE_DIR}/freshclam.conf.sample
    DESTINATION
        ${APP_CONFIG_DIRECTORY}/conf_examples)
