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

# Server Metrics 2026-03-19 01:47:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 14361.7 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166655
telemt_connections_bad_total 20306
telemt_connections_current 611
telemt_connections_me_current 611
telemt_handshake_timeouts_total 5010
telemt_upstream_connect_attempt_total 2874
telemt_upstream_connect_success_total 2827
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 2874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1484
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2119
telemt_me_reconnect_success_total 2112
telemt_me_reader_eof_total 2198
telemt_me_idle_close_by_peer_total 2198
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 48569
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134160
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 866
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 638
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 366
telemt_desync_frames_bucket_total{bucket="gt_10"} 177
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2118
telemt_me_writer_restored_same_endpoint_total 2098
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 131389
telemt_user_connections_current{user="hello"} 611
telemt_user_octets_from_client{user="hello"} 1358164288 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 43866908164 (40.85 GB)
telemt_user_unique_ips_current{user="hello"} 266
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 14365.6 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319407
telemt_connections_bad_total 21243
telemt_connections_current 1463
telemt_connections_me_current 1463
telemt_handshake_timeouts_total 5941
telemt_upstream_connect_attempt_total 2781
telemt_upstream_connect_success_total 2729
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 2781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 2013
telemt_me_reconnect_success_total 2006
telemt_me_reader_eof_total 2104
telemt_me_idle_close_by_peer_total 2104
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 99855
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 273712
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 973
telemt_desync_full_logged_total 333
telemt_desync_suppressed_total 640
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 359
telemt_desync_frames_bucket_total{bucket="gt_10"} 388
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2040
telemt_me_writer_restored_same_endpoint_total 1993
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 273754
telemt_user_connections_current{user="hello"} 1463
telemt_user_octets_from_client{user="hello"} 11302242284 (10.53 GB)
telemt_user_octets_to_client{user="hello"} 104777524328 (97.58 GB)
telemt_user_unique_ips_current{user="hello"} 581
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 14362.7 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257404
telemt_connections_bad_total 47957
telemt_connections_current 1150
telemt_connections_me_current 1150
telemt_handshake_timeouts_total 6373
telemt_upstream_connect_attempt_total 2759
telemt_upstream_connect_success_total 2759
telemt_upstream_connect_attempts_per_request{bucket="1"} 2759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2044
telemt_me_reconnect_success_total 2038
telemt_me_reader_eof_total 2145
telemt_me_idle_close_by_peer_total 2145
telemt_me_route_drop_no_conn_total 79296
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195647
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 946
telemt_desync_full_logged_total 344
telemt_desync_suppressed_total 602
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 377
telemt_desync_frames_bucket_total{bucket="gt_10"} 398
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2068
telemt_me_writer_restored_same_endpoint_total 2022
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 195638
telemt_user_connections_current{user="hello"} 1150
telemt_user_octets_from_client{user="hello"} 2384262996 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 116680625908 (108.67 GB)
telemt_user_unique_ips_current{user="hello"} 479
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 14416.3 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288151
telemt_connections_bad_total 27997
telemt_connections_current 942
telemt_connections_me_current 942
telemt_handshake_timeouts_total 4970
telemt_upstream_connect_attempt_total 2629
telemt_upstream_connect_success_total 2629
telemt_upstream_connect_attempts_per_request{bucket="1"} 2629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1267
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 1915
telemt_me_reconnect_success_total 1908
telemt_me_reader_eof_total 1998
telemt_me_idle_close_by_peer_total 1998
telemt_me_route_drop_no_conn_total 93189
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197624
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 556
telemt_desync_full_logged_total 202
telemt_desync_suppressed_total 354
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 227
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 1930
telemt_me_writer_restored_same_endpoint_total 1884
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 197540
telemt_user_connections_current{user="hello"} 942
telemt_user_octets_from_client{user="hello"} 1853586632 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 66474464968 (61.91 GB)
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 14359.5 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279095
telemt_connections_bad_total 16744
telemt_connections_current 1185
telemt_connections_me_current 1185
telemt_handshake_timeouts_total 9302
telemt_upstream_connect_attempt_total 2682
telemt_upstream_connect_success_total 2668
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1954
telemt_me_reconnect_success_total 1943
telemt_me_reader_eof_total 2037
telemt_me_idle_close_by_peer_total 2037
telemt_me_route_drop_no_conn_total 85897
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213643
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 845
telemt_desync_full_logged_total 326
telemt_desync_suppressed_total 519
telemt_desync_frames_bucket_total{bucket="1_2"} 228
telemt_desync_frames_bucket_total{bucket="3_10"} 299
telemt_desync_frames_bucket_total{bucket="gt_10"} 318
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 1954
telemt_me_writer_restored_same_endpoint_total 1919
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 213566
telemt_user_connections_current{user="hello"} 1185
telemt_user_octets_from_client{user="hello"} 6495515340 (6.05 GB)
telemt_user_octets_to_client{user="hello"} 118750068620 (110.59 GB)
telemt_user_unique_ips_current{user="hello"} 537
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 14370.9 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70066
telemt_connections_bad_total 9266
telemt_connections_current 313
telemt_connections_me_current 313
telemt_handshake_timeouts_total 255
telemt_upstream_connect_attempt_total 4044
telemt_upstream_connect_success_total 3925
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 4044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2078
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_reconnect_attempts_total 5039
telemt_me_reconnect_success_total 3208
telemt_me_reader_eof_total 3358
telemt_me_idle_close_by_peer_total 3358
telemt_me_route_drop_no_conn_total 27482
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58624
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3256
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 3178
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 58624
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 839219144 (800.34 MB)
telemt_user_octets_to_client{user="hello"} 39634528568 (36.91 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 14361.9 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197183
telemt_connections_bad_total 22168
telemt_connections_current 1029
telemt_connections_me_current 1029
telemt_handshake_timeouts_total 9220
telemt_upstream_connect_attempt_total 3057
telemt_upstream_connect_success_total 3057
telemt_upstream_connect_attempts_per_request{bucket="1"} 3057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1452
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2342
telemt_me_reconnect_success_total 2334
telemt_me_reader_eof_total 2449
telemt_me_idle_close_by_peer_total 2449
telemt_me_route_drop_no_conn_total 58554
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161033
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 983
telemt_desync_full_logged_total 392
telemt_desync_suppressed_total 591
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 414
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2361
telemt_me_writer_restored_same_endpoint_total 2319
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 161057
telemt_user_connections_current{user="hello"} 1029
telemt_user_octets_from_client{user="hello"} 1648959424 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 84031688376 (78.26 GB)
telemt_user_unique_ips_current{user="hello"} 427
telemt_user_unique_ips_recent_window{user="hello"} 80
```