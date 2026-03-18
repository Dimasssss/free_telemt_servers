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

# Server Metrics 2026-03-18 09:20:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 2382.2 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109881
telemt_connections_bad_total 242
telemt_handshake_timeouts_total 2301
telemt_upstream_connect_attempt_total 63361
telemt_upstream_connect_success_total 62450
telemt_upstream_connect_fail_total 911
telemt_upstream_connect_attempts_per_request{bucket="1"} 63361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 582
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 911
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 505868
telemt_me_reconnect_success_total 352
telemt_me_reader_eof_total 255
telemt_me_idle_close_by_peer_total 253
telemt_me_route_drop_no_conn_total 13027
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31882
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 93
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 296
telemt_me_refill_failed_total 16481
telemt_me_writer_restored_same_endpoint_total 247
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 93772
telemt_user_connections_current{user="hello"} 1560
telemt_user_octets_from_client{user="hello"} 1250999332 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 18573299681 (17.30 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 2413.3 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228524
telemt_connections_bad_total 32189
telemt_handshake_timeouts_total 4962
telemt_upstream_connect_attempt_total 455
telemt_upstream_connect_success_total 455
telemt_upstream_connect_attempts_per_request{bucket="1"} 455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 296
telemt_me_reconnect_success_total 287
telemt_me_reader_eof_total 241
telemt_me_idle_close_by_peer_total 241
telemt_me_route_drop_no_conn_total 73270
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175561
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 798
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 599
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 325
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 258
telemt_me_writer_restored_same_endpoint_total 286
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 174852
telemt_user_connections_current{user="hello"} 3504
telemt_user_octets_from_client{user="hello"} 5820613308 (5.42 GB)
telemt_user_octets_to_client{user="hello"} 58229328872 (54.23 GB)
telemt_user_unique_ips_current{user="hello"} 1033
telemt_user_unique_ips_recent_window{user="hello"} 533
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 2328.3 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196433
telemt_connections_bad_total 11098
telemt_handshake_timeouts_total 4122
telemt_upstream_connect_attempt_total 8747
telemt_upstream_connect_success_total 8747
telemt_upstream_connect_attempts_per_request{bucket="1"} 8747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1489
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 606054
telemt_me_reconnect_success_total 386
telemt_me_reader_eof_total 344
telemt_me_idle_close_by_peer_total 344
telemt_me_route_drop_no_conn_total 126367
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138429
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 231
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 142
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 89
telemt_me_writer_removed_unexpected_total 372
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 351
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 146505
telemt_user_connections_current{user="hello"} 2171
telemt_user_octets_from_client{user="hello"} 958959059 (914.53 MB)
telemt_user_octets_to_client{user="hello"} 32592242952 (30.35 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 628
telemt_user_unique_ips_recent_window{user="hello"} 346
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 2358.7 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202732
telemt_connections_bad_total 4858
telemt_handshake_timeouts_total 22563
telemt_upstream_connect_attempt_total 11146
telemt_upstream_connect_success_total 11063
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 11146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 893
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_reconnect_attempts_total 2810450
telemt_me_reconnect_success_total 624
telemt_me_reader_eof_total 588
telemt_me_idle_close_by_peer_total 588
telemt_me_route_drop_no_conn_total 79408
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148047
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 310
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 210
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_me_writer_removed_unexpected_total 610
telemt_me_refill_failed_total 99545
telemt_me_writer_restored_same_endpoint_total 529
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_user_connections_total{user="hello"} 158239
telemt_user_connections_current{user="hello"} 3564
telemt_user_octets_from_client{user="hello"} 1782133058 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 38796400765 (36.13 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 878
telemt_user_unique_ips_recent_window{user="hello"} 503
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 2253.3 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157835
telemt_connections_bad_total 6102
telemt_handshake_timeouts_total 1641
telemt_upstream_connect_attempt_total 10166
telemt_upstream_connect_success_total 10165
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 629
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2982450
telemt_me_reconnect_success_total 502
telemt_me_reader_eof_total 431
telemt_me_idle_close_by_peer_total 431
telemt_me_route_drop_no_conn_total 45006
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123376
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 342
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 217
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 123
telemt_desync_frames_bucket_total{bucket="gt_10"} 177
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 445
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 387
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 132790
telemt_user_connections_current{user="hello"} 2963
telemt_user_octets_from_client{user="hello"} 1870599729 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 51117947485 (47.61 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 861
telemt_user_unique_ips_recent_window{user="hello"} 454
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 2138.5 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45098
telemt_connections_bad_total 7552
telemt_handshake_timeouts_total 222
telemt_upstream_connect_attempt_total 370
telemt_upstream_connect_success_total 370
telemt_upstream_connect_attempts_per_request{bucket="1"} 370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 148
telemt_me_reconnect_attempts_total 205
telemt_me_reconnect_success_total 204
telemt_me_reader_eof_total 176
telemt_me_idle_close_by_peer_total 176
telemt_me_route_drop_no_conn_total 12609
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35433
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 190
telemt_me_writer_restored_same_endpoint_total 196
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 35391
telemt_user_connections_current{user="hello"} 910
telemt_user_octets_from_client{user="hello"} 832191440 (793.64 MB)
telemt_user_octets_to_client{user="hello"} 8382799596 (7.81 GB)
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 2209.4 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113658
telemt_connections_bad_total 748
telemt_handshake_timeouts_total 1951
telemt_upstream_connect_attempt_total 389
telemt_upstream_connect_success_total 375
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 138
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 216
telemt_me_reconnect_success_total 207
telemt_me_reader_eof_total 171
telemt_me_idle_close_by_peer_total 171
telemt_me_route_drop_no_conn_total 102497
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104489
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 288
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 195
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 193
telemt_me_writer_restored_same_endpoint_total 197
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 104401
telemt_user_connections_current{user="hello"} 1946
telemt_user_octets_from_client{user="hello"} 1327916608 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 39545999148 (36.83 GB)
telemt_user_unique_ips_current{user="hello"} 564
telemt_user_unique_ips_recent_window{user="hello"} 306
```