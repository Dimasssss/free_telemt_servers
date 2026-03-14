# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-14 06:16:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 168210.6 (46h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 646809
telemt_connections_bad_total 32325
telemt_handshake_timeouts_total 13018
telemt_upstream_connect_attempt_total 42824
telemt_upstream_connect_success_total 42608
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 42824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23015
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5606
telemt_me_reconnect_attempts_total 38546
telemt_me_reconnect_success_total 33857
telemt_me_reader_eof_total 36200
telemt_me_idle_close_by_peer_total 36199
telemt_me_route_drop_no_conn_total 212075
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 548927
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1975
telemt_desync_full_logged_total 676
telemt_desync_suppressed_total 1299
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 723
telemt_desync_frames_bucket_total{bucket="gt_10"} 824
telemt_pool_swap_total 155
telemt_me_writer_removed_unexpected_total 34370
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 33837
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 513
telemt_user_connections_total{user="hello"} 548812
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 16061173338 (14.96 GB)
telemt_user_octets_to_client{user="hello"} 266315658236 (248.03 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 168103.3 (46h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326286
telemt_connections_bad_total 2289
telemt_handshake_timeouts_total 2401
telemt_upstream_connect_attempt_total 149495
telemt_upstream_connect_success_total 148248
telemt_upstream_connect_fail_total 1247
telemt_upstream_connect_attempts_per_request{bucket="1"} 149495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36254
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2422
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1247
telemt_me_keepalive_timeout_total 3974
telemt_me_reconnect_attempts_total 175883
telemt_me_reconnect_success_total 36574
telemt_me_reader_eof_total 41885
telemt_me_idle_close_by_peer_total 41885
telemt_me_route_drop_no_conn_total 105692
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205985
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 41268
telemt_me_refill_failed_total 4347
telemt_me_writer_restored_same_endpoint_total 36557
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4694
telemt_user_connections_total{user="hello"} 309091
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 3221318907 (3.00 GB)
telemt_user_octets_to_client{user="hello"} 100798583127 (93.88 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 168067.2 (46h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 380485
telemt_connections_bad_total 2966
telemt_handshake_timeouts_total 34944
telemt_upstream_connect_attempt_total 44453
telemt_upstream_connect_success_total 44444
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 44453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24092
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3468
telemt_me_reconnect_attempts_total 37322
telemt_me_reconnect_success_total 36037
telemt_me_reader_eof_total 38753
telemt_me_idle_close_by_peer_total 38753
telemt_me_route_drop_no_conn_total 137125
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 329375
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 36473
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 36016
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 436
telemt_user_connections_total{user="hello"} 329148
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 13375781032 (12.46 GB)
telemt_user_octets_to_client{user="hello"} 130525645848 (121.56 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 168042.5 (46h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 481320
telemt_connections_bad_total 15657
telemt_handshake_timeouts_total 4485
telemt_upstream_connect_attempt_total 74716
telemt_upstream_connect_success_total 64153
telemt_upstream_connect_fail_total 10563
telemt_upstream_connect_attempts_per_request{bucket="1"} 74716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25861
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 339
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10563
telemt_me_keepalive_timeout_total 5386
telemt_me_reconnect_attempts_total 142813
telemt_me_reconnect_success_total 36756
telemt_me_reader_eof_total 41229
telemt_me_idle_close_by_peer_total 41221
telemt_me_route_drop_no_conn_total 173575
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 409330
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1753
telemt_desync_full_logged_total 519
telemt_desync_suppressed_total 1234
telemt_desync_frames_bucket_total{bucket="1_2"} 418
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 670
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 40490
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 36746
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3734
telemt_user_connections_total{user="hello"} 428175
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 9278854939 (8.64 GB)
telemt_user_octets_to_client{user="hello"} 171933372500 (160.13 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 118214.1 (32h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193080
telemt_connections_bad_total 28632
telemt_handshake_timeouts_total 1666
telemt_upstream_connect_attempt_total 42088
telemt_upstream_connect_success_total 41691
telemt_upstream_connect_fail_total 397
telemt_upstream_connect_attempts_per_request{bucket="1"} 42088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 397
telemt_me_keepalive_timeout_total 2451
telemt_me_reconnect_attempts_total 44337
telemt_me_reconnect_success_total 30911
telemt_me_reader_eof_total 33092
telemt_me_idle_close_by_peer_total 33092
telemt_me_route_drop_no_conn_total 57264
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152626
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 623
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 31613
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 30893
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 702
telemt_user_connections_total{user="hello"} 157375
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 2356487773 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 71629125639 (66.71 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 167998.7 (46h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 958922
telemt_connections_bad_total 35996
telemt_handshake_timeouts_total 25943
telemt_upstream_connect_attempt_total 34880
telemt_upstream_connect_success_total 34693
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 34880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18341
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_timeout_total 4687
telemt_me_reconnect_attempts_total 31064
telemt_me_reconnect_success_total 26387
telemt_me_reader_eof_total 28324
telemt_me_idle_close_by_peer_total 28321
telemt_me_route_drop_no_conn_total 452217
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 888846
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 26868
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 26380
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 481
telemt_user_connections_total{user="hello"} 861497
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 14888960412 (13.87 GB)
telemt_user_octets_to_client{user="hello"} 437748227220 (407.68 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 51
```