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

# Server Metrics 2026-03-14 06:32:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 169127.6 (46h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 649807
telemt_connections_bad_total 32344
telemt_handshake_timeouts_total 13044
telemt_upstream_connect_attempt_total 43044
telemt_upstream_connect_success_total 42827
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 43044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23124
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5633
telemt_me_reconnect_attempts_total 38722
telemt_me_reconnect_success_total 34032
telemt_me_reader_eof_total 36389
telemt_me_idle_close_by_peer_total 36388
telemt_me_route_drop_no_conn_total 213744
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 551779
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2010
telemt_desync_full_logged_total 687
telemt_desync_suppressed_total 1323
telemt_desync_frames_bucket_total{bucket="1_2"} 437
telemt_desync_frames_bucket_total{bucket="3_10"} 733
telemt_desync_frames_bucket_total{bucket="gt_10"} 840
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 34546
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 34012
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 551664
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 16101090942 (15.00 GB)
telemt_user_octets_to_client{user="hello"} 267253026376 (248.90 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 169020.9 (46h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 327723
telemt_connections_bad_total 2320
telemt_handshake_timeouts_total 2436
telemt_upstream_connect_attempt_total 149750
telemt_upstream_connect_success_total 148495
telemt_upstream_connect_fail_total 1255
telemt_upstream_connect_attempts_per_request{bucket="1"} 149750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2422
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1255
telemt_me_keepalive_timeout_total 3993
telemt_me_reconnect_attempts_total 177366
telemt_me_reconnect_success_total 36777
telemt_me_reader_eof_total 42130
telemt_me_idle_close_by_peer_total 42130
telemt_me_route_drop_no_conn_total 106780
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 207255
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
telemt_me_writer_removed_unexpected_total 41513
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 36760
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4736
telemt_user_connections_total{user="hello"} 310362
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 3238300543 (3.02 GB)
telemt_user_octets_to_client{user="hello"} 101167255431 (94.22 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 168984.6 (46h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 382482
telemt_connections_bad_total 2970
telemt_handshake_timeouts_total 35064
telemt_upstream_connect_attempt_total 44665
telemt_upstream_connect_success_total 44656
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 44665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24199
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3470
telemt_me_reconnect_attempts_total 37489
telemt_me_reconnect_success_total 36204
telemt_me_reader_eof_total 38930
telemt_me_idle_close_by_peer_total 38930
telemt_me_route_drop_no_conn_total 138018
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 331175
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
telemt_pool_swap_total 160
telemt_me_writer_removed_unexpected_total 36640
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 36183
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 436
telemt_user_connections_total{user="hello"} 330948
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 13417735784 (12.50 GB)
telemt_user_octets_to_client{user="hello"} 131008366044 (122.01 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 168960.2 (46h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 483168
telemt_connections_bad_total 15660
telemt_handshake_timeouts_total 4494
telemt_upstream_connect_attempt_total 74979
telemt_upstream_connect_success_total 64412
telemt_upstream_connect_fail_total 10567
telemt_upstream_connect_attempts_per_request{bucket="1"} 74979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26007
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10567
telemt_me_keepalive_timeout_total 5390
telemt_me_reconnect_attempts_total 143029
telemt_me_reconnect_success_total 36969
telemt_me_reader_eof_total 41469
telemt_me_idle_close_by_peer_total 41461
telemt_me_route_drop_no_conn_total 174345
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 411114
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1762
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 1239
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 669
telemt_desync_frames_bucket_total{bucket="gt_10"} 674
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 40705
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 36959
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3736
telemt_user_connections_total{user="hello"} 429959
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 9300629191 (8.66 GB)
telemt_user_octets_to_client{user="hello"} 175529076728 (163.47 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 119131.6 (33h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194506
telemt_connections_bad_total 28883
telemt_handshake_timeouts_total 1679
telemt_upstream_connect_attempt_total 42313
telemt_upstream_connect_success_total 41913
telemt_upstream_connect_fail_total 400
telemt_upstream_connect_attempts_per_request{bucket="1"} 42313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 400
telemt_me_keepalive_timeout_total 2453
telemt_me_reconnect_attempts_total 44516
telemt_me_reconnect_success_total 31089
telemt_me_reader_eof_total 33282
telemt_me_idle_close_by_peer_total 33282
telemt_me_route_drop_no_conn_total 57717
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153752
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 625
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 477
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 31792
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 31071
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 703
telemt_user_connections_total{user="hello"} 158501
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 2362829089 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 72150113123 (67.20 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 168916.2 (46h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 964519
telemt_connections_bad_total 36033
telemt_handshake_timeouts_total 26033
telemt_upstream_connect_attempt_total 35068
telemt_upstream_connect_success_total 34880
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 35068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_timeout_total 4695
telemt_me_reconnect_attempts_total 31208
telemt_me_reconnect_success_total 26531
telemt_me_reader_eof_total 28482
telemt_me_idle_close_by_peer_total 28479
telemt_me_route_drop_no_conn_total 454923
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 894169
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
telemt_pool_swap_total 160
telemt_me_writer_removed_unexpected_total 27015
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 26524
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 484
telemt_user_connections_total{user="hello"} 866818
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 14942586448 (13.92 GB)
telemt_user_octets_to_client{user="hello"} 438813664512 (408.68 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 59
```