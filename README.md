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

# Server Metrics 2026-03-19 01:22:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 12829.5 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146209
telemt_connections_bad_total 18167
telemt_connections_current 613
telemt_connections_me_current 613
telemt_handshake_timeouts_total 1936
telemt_upstream_connect_attempt_total 2610
telemt_upstream_connect_success_total 2565
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 2610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1900
telemt_me_reconnect_success_total 1895
telemt_me_reader_eof_total 1971
telemt_me_idle_close_by_peer_total 1971
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 44504
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119809
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 724
telemt_desync_full_logged_total 192
telemt_desync_suppressed_total 532
telemt_desync_frames_bucket_total{bucket="1_2"} 263
telemt_desync_frames_bucket_total{bucket="3_10"} 307
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1900
telemt_me_writer_restored_same_endpoint_total 1881
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 117041
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 1157868912 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 39809650176 (37.08 GB)
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 12833.5 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291162
telemt_connections_bad_total 20324
telemt_connections_current 1384
telemt_connections_me_current 1384
telemt_handshake_timeouts_total 4570
telemt_upstream_connect_attempt_total 2448
telemt_upstream_connect_success_total 2399
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 2448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 1728
telemt_me_reconnect_success_total 1722
telemt_me_reader_eof_total 1816
telemt_me_idle_close_by_peer_total 1816
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 90453
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249407
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 919
telemt_desync_full_logged_total 314
telemt_desync_suppressed_total 605
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 331
telemt_desync_frames_bucket_total{bucket="gt_10"} 373
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1752
telemt_me_writer_restored_same_endpoint_total 1709
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 249449
telemt_user_connections_current{user="hello"} 1384
telemt_user_octets_from_client{user="hello"} 11094809352 (10.33 GB)
telemt_user_octets_to_client{user="hello"} 95518650344 (88.96 GB)
telemt_user_unique_ips_current{user="hello"} 574
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 12830.8 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232795
telemt_connections_bad_total 41111
telemt_connections_current 1067
telemt_connections_me_current 1067
telemt_handshake_timeouts_total 5893
telemt_upstream_connect_attempt_total 2522
telemt_upstream_connect_success_total 2522
telemt_upstream_connect_attempts_per_request{bucket="1"} 2522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1248
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1850
telemt_me_reconnect_success_total 1845
telemt_me_reader_eof_total 1941
telemt_me_idle_close_by_peer_total 1941
telemt_me_route_drop_no_conn_total 73933
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 178837
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 865
telemt_desync_full_logged_total 317
telemt_desync_suppressed_total 548
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 343
telemt_desync_frames_bucket_total{bucket="gt_10"} 356
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1871
telemt_me_writer_restored_same_endpoint_total 1829
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 178833
telemt_user_connections_current{user="hello"} 1067
telemt_user_octets_from_client{user="hello"} 2215217628 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 105553742944 (98.30 GB)
telemt_user_unique_ips_current{user="hello"} 465
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 12884.0 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255123
telemt_connections_bad_total 27660
telemt_connections_current 881
telemt_connections_me_current 881
telemt_handshake_timeouts_total 4568
telemt_upstream_connect_attempt_total 2372
telemt_upstream_connect_success_total 2372
telemt_upstream_connect_attempts_per_request{bucket="1"} 2372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 1701
telemt_me_reconnect_success_total 1695
telemt_me_reader_eof_total 1774
telemt_me_idle_close_by_peer_total 1774
telemt_me_route_drop_no_conn_total 78899
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181023
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 504
telemt_desync_full_logged_total 185
telemt_desync_suppressed_total 319
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 204
telemt_desync_frames_bucket_total{bucket="gt_10"} 202
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1715
telemt_me_writer_restored_same_endpoint_total 1671
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 180941
telemt_user_connections_current{user="hello"} 881
telemt_user_octets_from_client{user="hello"} 1761651148 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 61827056468 (57.58 GB)
telemt_user_unique_ips_current{user="hello"} 395
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 12827.5 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255808
telemt_connections_bad_total 15509
telemt_connections_current 1156
telemt_connections_me_current 1156
telemt_handshake_timeouts_total 8346
telemt_upstream_connect_attempt_total 2424
telemt_upstream_connect_success_total 2411
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 1740
telemt_me_reconnect_success_total 1730
telemt_me_reader_eof_total 1813
telemt_me_idle_close_by_peer_total 1813
telemt_me_route_drop_no_conn_total 79229
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194776
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 794
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 490
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 283
telemt_desync_frames_bucket_total{bucket="gt_10"} 303
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1738
telemt_me_writer_restored_same_endpoint_total 1706
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 194699
telemt_user_connections_current{user="hello"} 1156
telemt_user_octets_from_client{user="hello"} 4080164840 (3.80 GB)
telemt_user_octets_to_client{user="hello"} 111895573128 (104.21 GB)
telemt_user_unique_ips_current{user="hello"} 521
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 12839.1 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64224
telemt_connections_bad_total 9112
telemt_connections_current 306
telemt_connections_me_current 306
telemt_handshake_timeouts_total 220
telemt_upstream_connect_attempt_total 3722
telemt_upstream_connect_success_total 3607
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 3722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1901
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_reconnect_attempts_total 4765
telemt_me_reconnect_success_total 2938
telemt_me_reader_eof_total 3075
telemt_me_idle_close_by_peer_total 3075
telemt_me_route_drop_no_conn_total 24373
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53266
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 27
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2985
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 2908
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 53266
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 774608232 (738.72 MB)
telemt_user_octets_to_client{user="hello"} 33391591636 (31.10 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 12829.7 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181159
telemt_connections_bad_total 21118
telemt_connections_current 1049
telemt_connections_me_current 1049
telemt_handshake_timeouts_total 8165
telemt_upstream_connect_attempt_total 2737
telemt_upstream_connect_success_total 2737
telemt_upstream_connect_attempts_per_request{bucket="1"} 2737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1297
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2066
telemt_me_reconnect_success_total 2060
telemt_me_reader_eof_total 2162
telemt_me_idle_close_by_peer_total 2162
telemt_me_route_drop_no_conn_total 54022
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147643
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 957
telemt_desync_full_logged_total 383
telemt_desync_suppressed_total 574
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 383
telemt_desync_frames_bucket_total{bucket="gt_10"} 402
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2083
telemt_me_writer_restored_same_endpoint_total 2045
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 147666
telemt_user_connections_current{user="hello"} 1049
telemt_user_octets_from_client{user="hello"} 1491821860 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 76681887408 (71.42 GB)
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 77
```