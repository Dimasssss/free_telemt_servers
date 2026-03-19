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

# Server Metrics 2026-03-19 01:17:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 12523.0 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142807
telemt_connections_bad_total 17727
telemt_connections_current 624
telemt_connections_me_current 624
telemt_handshake_timeouts_total 1686
telemt_upstream_connect_attempt_total 2514
telemt_upstream_connect_success_total 2471
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 2514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1849
telemt_me_reconnect_success_total 1844
telemt_me_reader_eof_total 1913
telemt_me_idle_close_by_peer_total 1913
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 43488
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117155
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 685
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 501
telemt_desync_frames_bucket_total{bucket="1_2"} 244
telemt_desync_frames_bucket_total{bucket="3_10"} 297
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1849
telemt_me_writer_restored_same_endpoint_total 1831
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 114387
telemt_user_connections_current{user="hello"} 624
telemt_user_octets_from_client{user="hello"} 1079725796 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 39374406140 (36.67 GB)
telemt_user_unique_ips_current{user="hello"} 264
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 12526.9 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285254
telemt_connections_bad_total 20016
telemt_connections_current 1458
telemt_connections_me_current 1458
telemt_handshake_timeouts_total 4229
telemt_upstream_connect_attempt_total 2355
telemt_upstream_connect_success_total 2305
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 2354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1092
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 1678
telemt_me_reconnect_success_total 1672
telemt_me_reader_eof_total 1758
telemt_me_idle_close_by_peer_total 1758
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 85568
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244425
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 906
telemt_desync_full_logged_total 308
telemt_desync_suppressed_total 598
telemt_desync_frames_bucket_total{bucket="1_2"} 211
telemt_desync_frames_bucket_total{bucket="3_10"} 324
telemt_desync_frames_bucket_total{bucket="gt_10"} 371
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1701
telemt_me_writer_restored_same_endpoint_total 1659
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 244465
telemt_user_connections_current{user="hello"} 1458
telemt_user_octets_from_client{user="hello"} 11054540820 (10.30 GB)
telemt_user_octets_to_client{user="hello"} 93746901948 (87.31 GB)
telemt_user_unique_ips_current{user="hello"} 590
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 12524.1 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228515
telemt_connections_bad_total 40137
telemt_connections_current 983
telemt_connections_me_current 983
telemt_handshake_timeouts_total 5734
telemt_upstream_connect_attempt_total 2425
telemt_upstream_connect_success_total 2425
telemt_upstream_connect_attempts_per_request{bucket="1"} 2425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1205
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1796
telemt_me_reconnect_success_total 1791
telemt_me_reader_eof_total 1879
telemt_me_idle_close_by_peer_total 1879
telemt_me_route_drop_no_conn_total 72687
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175755
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 858
telemt_desync_full_logged_total 313
telemt_desync_suppressed_total 545
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 352
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1817
telemt_me_writer_restored_same_endpoint_total 1775
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 175755
telemt_user_connections_current{user="hello"} 983
telemt_user_octets_from_client{user="hello"} 2192311080 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 103893698264 (96.76 GB)
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 12577.4 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249042
telemt_connections_bad_total 27592
telemt_connections_current 860
telemt_connections_me_current 860
telemt_handshake_timeouts_total 4510
telemt_upstream_connect_attempt_total 2269
telemt_upstream_connect_success_total 2269
telemt_upstream_connect_attempts_per_request{bucket="1"} 2269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 1641
telemt_me_reconnect_success_total 1635
telemt_me_reader_eof_total 1710
telemt_me_idle_close_by_peer_total 1710
telemt_me_route_drop_no_conn_total 78053
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177990
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 496
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 316
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 202
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1655
telemt_me_writer_restored_same_endpoint_total 1611
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 177908
telemt_user_connections_current{user="hello"} 860
telemt_user_octets_from_client{user="hello"} 1745075676 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 61029157892 (56.84 GB)
telemt_user_unique_ips_current{user="hello"} 390
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 12520.8 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250866
telemt_connections_bad_total 14661
telemt_connections_current 1109
telemt_connections_me_current 1109
telemt_handshake_timeouts_total 8235
telemt_upstream_connect_attempt_total 2325
telemt_upstream_connect_success_total 2312
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 1684
telemt_me_reconnect_success_total 1674
telemt_me_reader_eof_total 1750
telemt_me_idle_close_by_peer_total 1750
telemt_me_route_drop_no_conn_total 78108
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191258
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 766
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 469
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 274
telemt_desync_frames_bucket_total{bucket="gt_10"} 293
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1682
telemt_me_writer_restored_same_endpoint_total 1650
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 191182
telemt_user_connections_current{user="hello"} 1109
telemt_user_octets_from_client{user="hello"} 3672644036 (3.42 GB)
telemt_user_octets_to_client{user="hello"} 111066293308 (103.44 GB)
telemt_user_unique_ips_current{user="hello"} 512
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 12532.2 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62864
telemt_connections_bad_total 9069
telemt_connections_current 330
telemt_connections_me_current 330
telemt_handshake_timeouts_total 196
telemt_upstream_connect_attempt_total 3613
telemt_upstream_connect_success_total 3503
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 3613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1851
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_reconnect_attempts_total 4704
telemt_me_reconnect_success_total 2877
telemt_me_reader_eof_total 3000
telemt_me_idle_close_by_peer_total 3000
telemt_me_route_drop_no_conn_total 23820
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52003
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
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2924
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 2847
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 52003
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 762842528 (727.50 MB)
telemt_user_octets_to_client{user="hello"} 32799125168 (30.55 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 12523.1 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177607
telemt_connections_bad_total 20579
telemt_connections_current 1021
telemt_connections_me_current 1021
telemt_handshake_timeouts_total 7971
telemt_upstream_connect_attempt_total 2635
telemt_upstream_connect_success_total 2635
telemt_upstream_connect_attempts_per_request{bucket="1"} 2635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1248
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2007
telemt_me_reconnect_success_total 2001
telemt_me_reader_eof_total 2095
telemt_me_idle_close_by_peer_total 2095
telemt_me_route_drop_no_conn_total 52691
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144874
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 954
telemt_desync_full_logged_total 381
telemt_desync_suppressed_total 573
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 382
telemt_desync_frames_bucket_total{bucket="gt_10"} 400
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2023
telemt_me_writer_restored_same_endpoint_total 1986
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 144897
telemt_user_connections_current{user="hello"} 1021
telemt_user_octets_from_client{user="hello"} 1474608168 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 75392982208 (70.22 GB)
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 85
```