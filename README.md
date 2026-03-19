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

# Server Metrics 2026-03-19 03:55:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 22029.2 (6h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283275
telemt_connections_bad_total 32373
telemt_connections_current 794
telemt_connections_me_current 794
telemt_handshake_timeouts_total 18341
telemt_upstream_connect_attempt_total 4352
telemt_upstream_connect_success_total 4283
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 4351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3188
telemt_me_reconnect_success_total 3172
telemt_me_reader_eof_total 3332
telemt_me_idle_close_by_peer_total 3332
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 74343
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214647
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1537
telemt_desync_full_logged_total 417
telemt_desync_suppressed_total 1120
telemt_desync_frames_bucket_total{bucket="1_2"} 564
telemt_desync_frames_bucket_total{bucket="3_10"} 635
telemt_desync_frames_bucket_total{bucket="gt_10"} 338
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3194
telemt_me_writer_restored_same_endpoint_total 3155
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 211890
telemt_user_connections_current{user="hello"} 794
telemt_user_octets_from_client{user="hello"} 2368895716 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 62908775428 (58.59 GB)
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 22032.9 (6h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 525860
telemt_connections_bad_total 38385
telemt_connections_current 2113
telemt_connections_me_current 2113
telemt_handshake_timeouts_total 14941
telemt_upstream_connect_attempt_total 4188
telemt_upstream_connect_success_total 4114
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 4188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_reconnect_attempts_total 3007
telemt_me_reconnect_success_total 2993
telemt_me_reader_eof_total 3156
telemt_me_idle_close_by_peer_total 3156
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 154959
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 431333
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1636
telemt_desync_full_logged_total 558
telemt_desync_suppressed_total 1078
telemt_desync_frames_bucket_total{bucket="1_2"} 346
telemt_desync_frames_bucket_total{bucket="3_10"} 618
telemt_desync_frames_bucket_total{bucket="gt_10"} 672
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3038
telemt_me_writer_restored_same_endpoint_total 2976
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 431304
telemt_user_connections_current{user="hello"} 2113
telemt_user_octets_from_client{user="hello"} 13087075424 (12.19 GB)
telemt_user_octets_to_client{user="hello"} 184837359168 (172.14 GB)
telemt_user_unique_ips_current{user="hello"} 798
telemt_user_unique_ips_recent_window{user="hello"} 270
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 22030.3 (6h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428057
telemt_connections_bad_total 90647
telemt_connections_current 1653
telemt_connections_me_current 1653
telemt_handshake_timeouts_total 11260
telemt_upstream_connect_attempt_total 4138
telemt_upstream_connect_success_total 4138
telemt_upstream_connect_attempts_per_request{bucket="1"} 4138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2053
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 3031
telemt_me_reconnect_success_total 3021
telemt_me_reader_eof_total 3195
telemt_me_idle_close_by_peer_total 3195
telemt_me_route_drop_no_conn_total 125744
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312507
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1521
telemt_desync_full_logged_total 576
telemt_desync_suppressed_total 945
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 625
telemt_desync_frames_bucket_total{bucket="gt_10"} 636
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 3068
telemt_me_writer_restored_same_endpoint_total 3005
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 312503
telemt_user_connections_current{user="hello"} 1653
telemt_user_octets_from_client{user="hello"} 6611000048 (6.16 GB)
telemt_user_octets_to_client{user="hello"} 196684201468 (183.18 GB)
telemt_user_unique_ips_current{user="hello"} 631
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 22083.5 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520543
telemt_connections_bad_total 60922
telemt_connections_current 1469
telemt_connections_me_current 1469
telemt_handshake_timeouts_total 10489
telemt_upstream_connect_attempt_total 4014
telemt_upstream_connect_success_total 4014
telemt_upstream_connect_attempts_per_request{bucket="1"} 4014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1982
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2910
telemt_me_reconnect_success_total 2899
telemt_me_reader_eof_total 3055
telemt_me_idle_close_by_peer_total 3054
telemt_me_route_drop_no_conn_total 130453
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313420
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 872
telemt_desync_full_logged_total 313
telemt_desync_suppressed_total 559
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 376
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 2931
telemt_me_writer_restored_same_endpoint_total 2875
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 313160
telemt_user_connections_current{user="hello"} 1469
telemt_user_octets_from_client{user="hello"} 3777865120 (3.52 GB)
telemt_user_octets_to_client{user="hello"} 115401965404 (107.48 GB)
telemt_user_unique_ips_current{user="hello"} 557
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 22026.9 (6h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 529703
telemt_connections_bad_total 106802
telemt_connections_current 1723
telemt_connections_me_current 1723
telemt_handshake_timeouts_total 17157
telemt_upstream_connect_attempt_total 4154
telemt_upstream_connect_success_total 4126
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 3022
telemt_me_reconnect_success_total 3004
telemt_me_reader_eof_total 3169
telemt_me_idle_close_by_peer_total 3169
telemt_me_route_drop_no_conn_total 143970
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342259
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1486
telemt_desync_full_logged_total 571
telemt_desync_suppressed_total 915
telemt_desync_frames_bucket_total{bucket="1_2"} 376
telemt_desync_frames_bucket_total{bucket="3_10"} 601
telemt_desync_frames_bucket_total{bucket="gt_10"} 509
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3029
telemt_me_writer_restored_same_endpoint_total 2980
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 342176
telemt_user_connections_current{user="hello"} 1723
telemt_user_octets_from_client{user="hello"} 10716591972 (9.98 GB)
telemt_user_octets_to_client{user="hello"} 196183710940 (182.71 GB)
telemt_user_unique_ips_current{user="hello"} 704
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 22038.4 (6h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105181
telemt_connections_bad_total 10133
telemt_connections_current 404
telemt_connections_me_current 404
telemt_handshake_timeouts_total 479
telemt_upstream_connect_attempt_total 6120
telemt_upstream_connect_success_total 5954
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 6120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_reconnect_attempts_total 6679
telemt_me_reconnect_success_total 4841
telemt_me_reader_eof_total 5093
telemt_me_idle_close_by_peer_total 5093
telemt_me_route_drop_no_conn_total 43870
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91102
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 43
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 4907
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4811
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 91094
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 1711397556 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 59632306312 (55.54 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 22029.2 (6h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328498
telemt_connections_bad_total 36333
telemt_connections_current 1630
telemt_connections_me_current 1630
telemt_handshake_timeouts_total 17400
telemt_upstream_connect_attempt_total 4660
telemt_upstream_connect_success_total 4660
telemt_upstream_connect_attempts_per_request{bucket="1"} 4660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3556
telemt_me_reconnect_success_total 3545
telemt_me_reader_eof_total 3738
telemt_me_idle_close_by_peer_total 3738
telemt_me_route_drop_no_conn_total 91646
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 266028
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1314
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 808
telemt_desync_frames_bucket_total{bucket="1_2"} 246
telemt_desync_frames_bucket_total{bucket="3_10"} 517
telemt_desync_frames_bucket_total{bucket="gt_10"} 551
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 3584
telemt_me_writer_restored_same_endpoint_total 3530
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 266047
telemt_user_connections_current{user="hello"} 1630
telemt_user_octets_from_client{user="hello"} 2859070500 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 148086332080 (137.92 GB)
telemt_user_unique_ips_current{user="hello"} 585
telemt_user_unique_ips_recent_window{user="hello"} 181
```