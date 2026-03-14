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

# Server Metrics 2026-03-14 01:36:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 151406.3 (42h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 597417
telemt_connections_bad_total 21929
telemt_handshake_timeouts_total 12882
telemt_upstream_connect_attempt_total 38671
telemt_upstream_connect_success_total 38480
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 38671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20734
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5500
telemt_me_reconnect_attempts_total 35194
telemt_me_reconnect_success_total 30519
telemt_me_reader_eof_total 32608
telemt_me_idle_close_by_peer_total 32607
telemt_me_route_drop_no_conn_total 195961
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 511594
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1651
telemt_desync_full_logged_total 567
telemt_desync_suppressed_total 1084
telemt_desync_frames_bucket_total{bucket="1_2"} 354
telemt_desync_frames_bucket_total{bucket="3_10"} 622
telemt_desync_frames_bucket_total{bucket="gt_10"} 675
telemt_pool_swap_total 137
telemt_me_writer_removed_unexpected_total 31001
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 30503
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 482
telemt_user_connections_total{user="hello"} 511489
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 15571378234 (14.50 GB)
telemt_user_octets_to_client{user="hello"} 252110584172 (234.80 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 151299.4 (42h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306102
telemt_connections_bad_total 2237
telemt_handshake_timeouts_total 1940
telemt_upstream_connect_attempt_total 143100
telemt_upstream_connect_success_total 141985
telemt_upstream_connect_fail_total 1115
telemt_upstream_connect_attempts_per_request{bucket="1"} 143100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32572
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1115
telemt_me_keepalive_timeout_total 3800
telemt_me_reconnect_attempts_total 162061
telemt_me_reconnect_success_total 31114
telemt_me_reader_eof_total 36010
telemt_me_idle_close_by_peer_total 36010
telemt_me_route_drop_no_conn_total 96681
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187096
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 39
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
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 35498
telemt_me_refill_failed_total 4086
telemt_me_writer_restored_same_endpoint_total 31097
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4384
telemt_user_connections_total{user="hello"} 290208
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 3035410615 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 90723618587 (84.49 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 151263.2 (42h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358481
telemt_connections_bad_total 2823
telemt_handshake_timeouts_total 33213
telemt_upstream_connect_attempt_total 40115
telemt_upstream_connect_success_total 40109
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 40115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21719
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3284
telemt_me_reconnect_attempts_total 33788
telemt_me_reconnect_success_total 32524
telemt_me_reader_eof_total 34941
telemt_me_idle_close_by_peer_total 34941
telemt_me_route_drop_no_conn_total 127461
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 309947
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
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
telemt_pool_swap_total 141
telemt_me_writer_removed_unexpected_total 32909
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 32504
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 385
telemt_user_connections_total{user="hello"} 309832
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 12612920920 (11.75 GB)
telemt_user_octets_to_client{user="hello"} 127009057584 (118.29 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 151238.9 (42h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 459789
telemt_connections_bad_total 15375
telemt_handshake_timeouts_total 4343
telemt_upstream_connect_attempt_total 68702
telemt_upstream_connect_success_total 58253
telemt_upstream_connect_fail_total 10449
telemt_upstream_connect_attempts_per_request{bucket="1"} 68702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22632
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 321
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10449
telemt_me_keepalive_timeout_total 5084
telemt_me_reconnect_attempts_total 136676
telemt_me_reconnect_success_total 31698
telemt_me_reader_eof_total 35889
telemt_me_idle_close_by_peer_total 35881
telemt_me_route_drop_no_conn_total 162324
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 389671
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1708
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 646
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 35359
telemt_me_refill_failed_total 3274
telemt_me_writer_restored_same_endpoint_total 31688
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3661
telemt_user_connections_total{user="hello"} 408513
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 9067957327 (8.45 GB)
telemt_user_octets_to_client{user="hello"} 156763982024 (146.00 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 101410.4 (28h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169335
telemt_connections_bad_total 24683
telemt_handshake_timeouts_total 1557
telemt_upstream_connect_attempt_total 37171
telemt_upstream_connect_success_total 36830
telemt_upstream_connect_fail_total 341
telemt_upstream_connect_attempts_per_request{bucket="1"} 37171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17966
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 341
telemt_me_keepalive_timeout_total 1387
telemt_me_reconnect_attempts_total 40297
telemt_me_reconnect_success_total 26884
telemt_me_reader_eof_total 28753
telemt_me_idle_close_by_peer_total 28753
telemt_me_route_drop_no_conn_total 50382
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133309
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 27546
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 26866
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 662
telemt_user_connections_total{user="hello"} 138115
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 1881172901 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 64294314031 (59.88 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 151194.7 (41h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 880973
telemt_connections_bad_total 27500
telemt_handshake_timeouts_total 25323
telemt_upstream_connect_attempt_total 31261
telemt_upstream_connect_success_total 31094
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 31261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 3491
telemt_me_reconnect_attempts_total 28285
telemt_me_reconnect_success_total 23619
telemt_me_reader_eof_total 25296
telemt_me_idle_close_by_peer_total 25293
telemt_me_route_drop_no_conn_total 419422
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 823323
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 706
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 252
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 140
telemt_me_writer_removed_unexpected_total 24073
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23612
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 796079
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 14135714728 (13.16 GB)
telemt_user_octets_to_client{user="hello"} 405813395576 (377.94 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 30
```