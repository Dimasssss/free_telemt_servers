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

# Server Metrics 2026-03-13 10:17:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 96264.3 (26h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 382122
telemt_connections_bad_total 3192
telemt_handshake_timeouts_total 8086
telemt_upstream_connect_attempt_total 24303
telemt_upstream_connect_success_total 24191
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 24303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1754
telemt_me_reconnect_attempts_total 22892
telemt_me_reconnect_success_total 19373
telemt_me_reader_eof_total 20692
telemt_me_idle_close_by_peer_total 20691
telemt_me_route_drop_no_conn_total 119416
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 328863
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1073
telemt_desync_full_logged_total 396
telemt_desync_suppressed_total 677
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 396
telemt_desync_frames_bucket_total{bucket="gt_10"} 460
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 19684
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 19357
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 328567
telemt_user_connections_current{user="hello"} 423
telemt_user_octets_from_client{user="hello"} 5777725980 (5.38 GB)
telemt_user_octets_to_client{user="hello"} 142898291016 (133.08 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 96157.1 (26h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175097
telemt_connections_bad_total 1563
telemt_handshake_timeouts_total 1322
telemt_upstream_connect_attempt_total 47327
telemt_upstream_connect_success_total 46677
telemt_upstream_connect_fail_total 650
telemt_upstream_connect_attempts_per_request{bucket="1"} 47327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 650
telemt_me_keepalive_timeout_total 736
telemt_me_reconnect_attempts_total 84376
telemt_me_reconnect_success_total 25389
telemt_me_reader_eof_total 27981
telemt_me_idle_close_by_peer_total 27981
telemt_me_route_drop_no_conn_total 74908
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148560
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 20
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
telemt_me_writer_removed_unexpected_total 27447
telemt_me_refill_failed_total 1840
telemt_me_writer_restored_same_endpoint_total 25373
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2058
telemt_user_connections_total{user="hello"} 164840
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 1715011128 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 54493395991 (50.75 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 96120.6 (26h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213304
telemt_connections_bad_total 2046
telemt_handshake_timeouts_total 4284
telemt_upstream_connect_attempt_total 25998
telemt_upstream_connect_success_total 25995
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 25998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14002
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 740
telemt_me_reconnect_attempts_total 22348
telemt_me_reconnect_success_total 21151
telemt_me_reader_eof_total 22664
telemt_me_idle_close_by_peer_total 22664
telemt_me_route_drop_no_conn_total 80112
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199186
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 21383
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 21131
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 199107
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 9177749892 (8.55 GB)
telemt_user_octets_to_client{user="hello"} 81682883492 (76.07 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 96096.6 (26h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301622
telemt_connections_bad_total 13675
telemt_handshake_timeouts_total 2230
telemt_upstream_connect_attempt_total 38819
telemt_upstream_connect_success_total 28798
telemt_upstream_connect_fail_total 10021
telemt_upstream_connect_attempts_per_request{bucket="1"} 38819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14165
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 192
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10021
telemt_me_keepalive_timeout_total 3433
telemt_me_reconnect_attempts_total 81716
telemt_me_reconnect_success_total 21144
telemt_me_reader_eof_total 23682
telemt_me_idle_close_by_peer_total 23675
telemt_me_route_drop_no_conn_total 108862
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 258728
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 966
telemt_desync_full_logged_total 285
telemt_desync_suppressed_total 681
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 356
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 23304
telemt_me_refill_failed_total 1888
telemt_me_writer_restored_same_endpoint_total 21134
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2160
telemt_user_connections_total{user="hello"} 261450
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 5656950066 (5.27 GB)
telemt_user_octets_to_client{user="hello"} 97678199641 (90.97 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 46268.3 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62219
telemt_connections_bad_total 9257
telemt_handshake_timeouts_total 492
telemt_upstream_connect_attempt_total 16043
telemt_upstream_connect_success_total 15887
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 16043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8856
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 400
telemt_me_reconnect_attempts_total 15789
telemt_me_reconnect_success_total 13559
telemt_me_reader_eof_total 14424
telemt_me_idle_close_by_peer_total 14424
telemt_me_route_drop_no_conn_total 19309
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50616
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 76
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 13751
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 13541
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 50611
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 464143516 (442.64 MB)
telemt_user_octets_to_client{user="hello"} 13595116232 (12.66 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 96053.7 (26h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 525863
telemt_connections_bad_total 14507
telemt_handshake_timeouts_total 7609
telemt_upstream_connect_attempt_total 20519
telemt_upstream_connect_success_total 20412
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 20519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10828
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1582
telemt_me_reconnect_attempts_total 19292
telemt_me_reconnect_success_total 15637
telemt_me_reader_eof_total 16764
telemt_me_idle_close_by_peer_total 16761
telemt_me_route_drop_no_conn_total 270267
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 512137
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 423
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 262
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 156
telemt_desync_frames_bucket_total{bucket="gt_10"} 163
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 15957
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 15630
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 320
telemt_user_connections_total{user="hello"} 485219
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 8660459700 (8.07 GB)
telemt_user_octets_to_client{user="hello"} 272989483988 (254.24 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 73
```