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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-17 09:38:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 53560.2 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 421568
telemt_connections_bad_total 3663
telemt_handshake_timeouts_total 12257
telemt_upstream_connect_attempt_total 13679
telemt_upstream_connect_success_total 13247
telemt_upstream_connect_fail_total 432
telemt_upstream_connect_attempts_per_request{bucket="1"} 13679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 432
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 9807
telemt_me_reconnect_success_total 8284
telemt_me_reader_eof_total 8803
telemt_me_idle_close_by_peer_total 8802
telemt_me_route_drop_no_conn_total 132950
telemt_me_route_drop_channel_closed_total 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 379844
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3028
telemt_desync_full_logged_total 822
telemt_desync_suppressed_total 2206
telemt_desync_frames_bucket_total{bucket="1_2"} 745
telemt_desync_frames_bucket_total{bucket="3_10"} 1344
telemt_desync_frames_bucket_total{bucket="gt_10"} 939
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8454
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 8262
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 381832
telemt_user_connections_current{user="hello"} 1019
telemt_user_octets_from_client{user="hello"} 5502729087 (5.12 GB)
telemt_user_octets_to_client{user="hello"} 152623679159 (142.14 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 333
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 53811.7 (14h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229399
telemt_connections_bad_total 2518
telemt_handshake_timeouts_total 13233
telemt_upstream_connect_attempt_total 14091
telemt_upstream_connect_success_total 13901
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 14091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 18608
telemt_me_reconnect_success_total 11244
telemt_me_reader_eof_total 12036
telemt_me_idle_close_by_peer_total 12036
telemt_me_route_drop_no_conn_total 83805
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202028
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 540
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 341
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11587
telemt_me_refill_failed_total 229
telemt_me_writer_restored_same_endpoint_total 11228
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 343
telemt_user_connections_total{user="hello"} 202030
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 2458848732 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 78463164612 (73.07 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 53587.8 (14h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141081
telemt_connections_bad_total 7577
telemt_handshake_timeouts_total 9673
telemt_upstream_connect_attempt_total 14304
telemt_upstream_connect_success_total 14229
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 14304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7877
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 12495
telemt_me_reconnect_success_total 11529
telemt_me_reader_eof_total 12321
telemt_me_idle_close_by_peer_total 12321
telemt_me_route_drop_no_conn_total 42927
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114481
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 349
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 258
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 147
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 11707
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 11518
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 114404
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 7546145020 (7.03 GB)
telemt_user_octets_to_client{user="hello"} 35500232912 (33.06 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 53646.9 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309388
telemt_connections_bad_total 6191
telemt_handshake_timeouts_total 10879
telemt_upstream_connect_attempt_total 12206
telemt_upstream_connect_success_total 12093
telemt_upstream_connect_fail_total 113
telemt_upstream_connect_attempts_per_request{bucket="1"} 12206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6314
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 10439
telemt_me_reconnect_success_total 9354
telemt_me_reader_eof_total 9948
telemt_me_idle_close_by_peer_total 9948
telemt_me_route_drop_no_conn_total 85378
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248511
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 542
telemt_desync_full_logged_total 202
telemt_desync_suppressed_total 340
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 241
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9533
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 9346
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 248470
telemt_user_connections_current{user="hello"} 711
telemt_user_octets_from_client{user="hello"} 2655987078 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 100535925317 (93.63 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 53619.0 (14h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173580
telemt_connections_bad_total 47356
telemt_handshake_timeouts_total 2771
telemt_upstream_connect_attempt_total 16351
telemt_upstream_connect_success_total 16138
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 16351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8726
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_reconnect_attempts_total 20459
telemt_me_reconnect_success_total 13343
telemt_me_reader_eof_total 14153
telemt_me_idle_close_by_peer_total 14153
telemt_me_route_drop_no_conn_total 45201
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118149
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 373
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 278
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 13731
telemt_me_refill_failed_total 220
telemt_me_writer_restored_same_endpoint_total 13335
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 388
telemt_user_connections_total{user="hello"} 118178
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 1821515227 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 53495376534 (49.82 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 53780.3 (14h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 408658
telemt_connections_bad_total 48117
telemt_handshake_timeouts_total 4136
telemt_upstream_connect_attempt_total 10987
telemt_upstream_connect_success_total 10928
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 10987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5546
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 12140
telemt_me_reconnect_success_total 8260
telemt_me_reader_eof_total 8920
telemt_me_idle_close_by_peer_total 8920
telemt_me_route_drop_no_conn_total 272148
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 412052
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 580
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 347
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 206
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8510
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 8246
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 333941
telemt_user_connections_current{user="hello"} 866
telemt_user_octets_from_client{user="hello"} 4794740916 (4.47 GB)
telemt_user_octets_to_client{user="hello"} 186291336448 (173.50 GB)
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 1546.8 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1554
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 446
telemt_upstream_connect_success_total 426
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 223
telemt_me_reconnect_success_total 203
telemt_me_reader_eof_total 199
telemt_me_idle_close_by_peer_total 199
telemt_me_route_drop_no_conn_total 396
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1326
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 211
telemt_me_writer_restored_same_endpoint_total 201
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 1432
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 18915445 (18.04 MB)
telemt_user_octets_to_client{user="hello"} 5542381630 (5.16 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 8
```