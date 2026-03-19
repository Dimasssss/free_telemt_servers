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

# Server Metrics 2026-03-19 00:26:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 9455.4 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109161
telemt_connections_bad_total 12240
telemt_connections_current 664
telemt_connections_me_current 664
telemt_handshake_timeouts_total 1127
telemt_upstream_connect_attempt_total 1873
telemt_upstream_connect_success_total 1843
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 1873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1350
telemt_me_reconnect_success_total 1346
telemt_me_reader_eof_total 1390
telemt_me_idle_close_by_peer_total 1390
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 34406
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90930
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 536
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 380
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1347
telemt_me_writer_restored_same_endpoint_total 1334
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 88165
telemt_user_connections_current{user="hello"} 664
telemt_user_octets_from_client{user="hello"} 802536560 (765.36 MB)
telemt_user_octets_to_client{user="hello"} 34203026364 (31.85 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 9459.4 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233226
telemt_connections_bad_total 19063
telemt_connections_current 1596
telemt_connections_me_current 1596
telemt_handshake_timeouts_total 2188
telemt_upstream_connect_attempt_total 1797
telemt_upstream_connect_success_total 1758
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 1797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 925
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 1259
telemt_me_reconnect_success_total 1258
telemt_me_reader_eof_total 1314
telemt_me_idle_close_by_peer_total 1314
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 71298
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 198850
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 787
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 521
telemt_desync_frames_bucket_total{bucket="1_2"} 177
telemt_desync_frames_bucket_total{bucket="3_10"} 272
telemt_desync_frames_bucket_total{bucket="gt_10"} 338
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1278
telemt_me_writer_restored_same_endpoint_total 1245
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 198907
telemt_user_connections_current{user="hello"} 1596
telemt_user_octets_from_client{user="hello"} 10616017496 (9.89 GB)
telemt_user_octets_to_client{user="hello"} 74165184884 (69.07 GB)
telemt_user_unique_ips_current{user="hello"} 614
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 9456.4 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182329
telemt_connections_bad_total 28661
telemt_connections_current 1075
telemt_connections_me_current 1075
telemt_handshake_timeouts_total 4865
telemt_upstream_connect_attempt_total 1855
telemt_upstream_connect_success_total 1855
telemt_upstream_connect_attempts_per_request{bucket="1"} 1855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 921
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1356
telemt_me_reconnect_success_total 1352
telemt_me_reader_eof_total 1410
telemt_me_idle_close_by_peer_total 1410
telemt_me_route_drop_no_conn_total 60241
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143217
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 647
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 399
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 261
telemt_desync_frames_bucket_total{bucket="gt_10"} 261
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1370
telemt_me_writer_restored_same_endpoint_total 1336
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 143218
telemt_user_connections_current{user="hello"} 1075
telemt_user_octets_from_client{user="hello"} 1909064100 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 83574866284 (77.84 GB)
telemt_user_unique_ips_current{user="hello"} 477
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 9509.8 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190873
telemt_connections_bad_total 26219
telemt_connections_current 954
telemt_connections_me_current 954
telemt_handshake_timeouts_total 3477
telemt_upstream_connect_attempt_total 1765
telemt_upstream_connect_success_total 1765
telemt_upstream_connect_attempts_per_request{bucket="1"} 1765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 836
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 1268
telemt_me_reconnect_success_total 1262
telemt_me_reader_eof_total 1313
telemt_me_idle_close_by_peer_total 1313
telemt_me_route_drop_no_conn_total 69788
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147676
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 394
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 253
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 161
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1278
telemt_me_writer_restored_same_endpoint_total 1238
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 147601
telemt_user_connections_current{user="hello"} 954
telemt_user_octets_from_client{user="hello"} 1575810180 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 53506156260 (49.83 GB)
telemt_user_unique_ips_current{user="hello"} 409
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 9453.2 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198259
telemt_connections_bad_total 8643
telemt_connections_current 1123
telemt_connections_me_current 1123
telemt_handshake_timeouts_total 6836
telemt_upstream_connect_attempt_total 1778
telemt_upstream_connect_success_total 1767
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1268
telemt_me_reconnect_success_total 1261
telemt_me_reader_eof_total 1312
telemt_me_idle_close_by_peer_total 1312
telemt_me_route_drop_no_conn_total 63919
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154520
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 247
telemt_desync_suppressed_total 372
telemt_desync_frames_bucket_total{bucket="1_2"} 148
telemt_desync_frames_bucket_total{bucket="3_10"} 213
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1267
telemt_me_writer_restored_same_endpoint_total 1237
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 154450
telemt_user_connections_current{user="hello"} 1123
telemt_user_octets_from_client{user="hello"} 2041209372 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 96365338812 (89.75 GB)
telemt_user_unique_ips_current{user="hello"} 508
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 9464.9 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49723
telemt_connections_bad_total 8601
telemt_connections_current 343
telemt_connections_me_current 343
telemt_handshake_timeouts_total 149
telemt_upstream_connect_attempt_total 2844
telemt_upstream_connect_success_total 2754
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 2844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1398
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_reconnect_attempts_total 4084
telemt_me_reconnect_success_total 2257
telemt_me_reader_eof_total 2338
telemt_me_idle_close_by_peer_total 2338
telemt_me_route_drop_no_conn_total 18196
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39831
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
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2297
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 2227
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 39832
telemt_user_connections_current{user="hello"} 343
telemt_user_octets_from_client{user="hello"} 455437988 (434.34 MB)
telemt_user_octets_to_client{user="hello"} 26534782816 (24.71 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 9455.5 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145629
telemt_connections_bad_total 18241
telemt_connections_current 1003
telemt_connections_me_current 1003
telemt_handshake_timeouts_total 5468
telemt_upstream_connect_attempt_total 1950
telemt_upstream_connect_success_total 1950
telemt_upstream_connect_attempts_per_request{bucket="1"} 1950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 937
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1451
telemt_me_reconnect_success_total 1446
telemt_me_reader_eof_total 1508
telemt_me_idle_close_by_peer_total 1508
telemt_me_route_drop_no_conn_total 43797
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119125
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 822
telemt_desync_full_logged_total 325
telemt_desync_suppressed_total 497
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 347
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1463
telemt_me_writer_restored_same_endpoint_total 1431
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 119150
telemt_user_connections_current{user="hello"} 1003
telemt_user_octets_from_client{user="hello"} 1142463344 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 63154623228 (58.82 GB)
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 62
```