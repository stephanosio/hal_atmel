zephyr_include_directories(
  ./
  $ENV{ZEPHYR_BASE}/include/drivers
  )

zephyr_sources(
  driver/source/m2m_ate_mode.c
  driver/source/m2m_crypto.c
  driver/source/m2m_hif.c
  driver/source/m2m_ota.c
  driver/source/m2m_periph.c
  driver/source/m2m_wifi.c
  driver/source/nmasic.c
  driver/source/nmbus.c
  driver/source/nmdrv.c
  driver/source/nmspi.c
  socket/source/socket.c
  common/source/nm_common.c
  spi_flash/source/spi_flash.c
  )
