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

# Server Metrics 2026-03-13 17:02:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 120548.0 (33h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 505799
telemt_connections_bad_total 5654
telemt_handshake_timeouts_total 10955
telemt_upstream_connect_attempt_total 29897
telemt_upstream_connect_success_total 29751
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 29897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16225
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3299
telemt_me_reconnect_attempts_total 27283
telemt_me_reconnect_success_total 23737
telemt_me_reader_eof_total 25361
telemt_me_idle_close_by_peer_total 25360
telemt_me_route_drop_no_conn_total 164734
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 441705
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1422
telemt_desync_full_logged_total 497
telemt_desync_suppressed_total 925
telemt_desync_frames_bucket_total{bucket="1_2"} 316
telemt_desync_frames_bucket_total{bucket="3_10"} 512
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24105
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 23721
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 441275
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 8030341316 (7.48 GB)
telemt_user_octets_to_client{user="hello"} 204645386664 (190.59 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 120440.7 (33h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247367
telemt_connections_bad_total 1899
telemt_handshake_timeouts_total 1799
telemt_upstream_connect_attempt_total 102416
telemt_upstream_connect_success_total 101598
telemt_upstream_connect_fail_total 818
telemt_upstream_connect_attempts_per_request{bucket="1"} 102416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 818
telemt_me_keepalive_timeout_total 1481
telemt_me_reconnect_attempts_total 121824
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29780
telemt_me_idle_close_by_peer_total 29780
telemt_me_route_drop_no_conn_total 82187
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164771
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 29250
telemt_me_refill_failed_total 2989
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3217
telemt_user_connections_total{user="hello"} 234117
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 2442521666 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 72488120235 (67.51 GB)
telemt_user_msgs_from_client{user="hello"} 1087614
telemt_user_msgs_to_client{user="hello"} 6386431
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 120404.4 (33h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293825
telemt_connections_bad_total 2449
telemt_handshake_timeouts_total 15462
telemt_upstream_connect_attempt_total 32188
telemt_upstream_connect_success_total 32184
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 32188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17218
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2489
telemt_me_reconnect_attempts_total 27357
telemt_me_reconnect_success_total 26132
telemt_me_reader_eof_total 28005
telemt_me_idle_close_by_peer_total 28005
telemt_me_route_drop_no_conn_total 105242
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 265534
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 26423
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 26112
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 291
telemt_user_connections_total{user="hello"} 265443
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 10117974372 (9.42 GB)
telemt_user_octets_to_client{user="hello"} 110779576844 (103.17 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 120379.8 (33h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 398889
telemt_connections_bad_total 15099
telemt_handshake_timeouts_total 3837
telemt_upstream_connect_attempt_total 52679
telemt_upstream_connect_success_total 42470
telemt_upstream_connect_fail_total 10209
telemt_upstream_connect_attempts_per_request{bucket="1"} 52679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17066
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10209
telemt_me_keepalive_timeout_total 4229
telemt_me_reconnect_attempts_total 111341
telemt_me_reconnect_success_total 24414
telemt_me_reader_eof_total 27835
telemt_me_idle_close_by_peer_total 27828
telemt_me_route_drop_no_conn_total 139769
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338528
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1350
telemt_desync_full_logged_total 402
telemt_desync_suppressed_total 948
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 27438
telemt_me_refill_failed_total 2711
telemt_me_writer_restored_same_endpoint_total 24404
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3024
telemt_user_connections_total{user="hello"} 350439
telemt_user_connections_current{user="hello"} 243
telemt_user_octets_from_client{user="hello"} 8279603271 (7.71 GB)
telemt_user_octets_to_client{user="hello"} 127641534398 (118.88 GB)
telemt_user_msgs_from_client{user="hello"} 373344
telemt_user_msgs_to_client{user="hello"} 570748
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 70551.5 (19h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113642
telemt_connections_bad_total 14636
telemt_handshake_timeouts_total 1377
telemt_upstream_connect_attempt_total 28280
telemt_upstream_connect_success_total 28026
telemt_upstream_connect_fail_total 254
telemt_upstream_connect_attempts_per_request{bucket="1"} 28280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 254
telemt_me_keepalive_timeout_total 1129
telemt_me_reconnect_attempts_total 31621
telemt_me_reconnect_success_total 19579
telemt_me_reader_eof_total 20977
telemt_me_idle_close_by_peer_total 20977
telemt_me_route_drop_no_conn_total 35202
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89057
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 20133
telemt_me_refill_failed_total 374
telemt_me_writer_restored_same_endpoint_total 19561
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 93955
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 1121604513 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 28906402063 (26.92 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 120336.5 (33h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 734472
telemt_connections_bad_total 24642
telemt_handshake_timeouts_total 24309
telemt_upstream_connect_attempt_total 25171
telemt_upstream_connect_success_total 25044
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 25171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 2656
telemt_me_reconnect_attempts_total 23704
telemt_me_reconnect_success_total 19069
telemt_me_reader_eof_total 20461
telemt_me_idle_close_by_peer_total 20458
telemt_me_route_drop_no_conn_total 346900
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 688652
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 667
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 19457
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19062
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 388
telemt_user_connections_total{user="hello"} 661539
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 11469114748 (10.68 GB)
telemt_user_octets_to_client{user="hello"} 334902896260 (311.90 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 65
```