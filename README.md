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

# Server Metrics 2026-03-12 11:00:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 12456.4 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65093
telemt_connections_bad_total 493
telemt_handshake_timeouts_total 2591
telemt_upstream_connect_attempt_total 3059
telemt_upstream_connect_success_total 3047
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1668
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 2415
telemt_me_reconnect_success_total 2401
telemt_me_reader_eof_total 2489
telemt_me_idle_close_by_peer_total 2488
telemt_me_route_drop_no_conn_total 17589
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58709
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 235
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2413
telemt_me_writer_restored_same_endpoint_total 2385
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 58685
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 801801856 (764.66 MB)
telemt_user_octets_to_client{user="hello"} 17704185428 (16.49 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 12349.3 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26247
telemt_connections_bad_total 219
telemt_handshake_timeouts_total 196
telemt_upstream_connect_attempt_total 4419
telemt_upstream_connect_success_total 4330
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 4419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 9942
telemt_me_reconnect_success_total 3689
telemt_me_reader_eof_total 3928
telemt_me_idle_close_by_peer_total 3928
telemt_me_route_drop_no_conn_total 10151
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24977
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 3898
telemt_me_refill_failed_total 195
telemt_me_writer_restored_same_endpoint_total 3674
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 24975
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 261963220 (249.83 MB)
telemt_user_octets_to_client{user="hello"} 5465118920 (5.09 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 12312.7 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37236
telemt_connections_bad_total 102
telemt_handshake_timeouts_total 283
telemt_upstream_connect_attempt_total 3437
telemt_upstream_connect_success_total 3437
telemt_upstream_connect_attempts_per_request{bucket="1"} 3437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2801
telemt_me_reconnect_success_total 2783
telemt_me_reader_eof_total 2908
telemt_me_idle_close_by_peer_total 2908
telemt_me_route_drop_no_conn_total 11967
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34865
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2786
telemt_me_writer_restored_same_endpoint_total 2763
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 34853
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 467460420 (445.80 MB)
telemt_user_octets_to_client{user="hello"} 29310620608 (27.30 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 12288.4 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45121
telemt_connections_bad_total 1034
telemt_handshake_timeouts_total 238
telemt_upstream_connect_attempt_total 3614
telemt_upstream_connect_success_total 3532
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 3614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 2920
telemt_me_reconnect_success_total 2881
telemt_me_reader_eof_total 2992
telemt_me_idle_close_by_peer_total 2992
telemt_me_route_drop_no_conn_total 14006
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40984
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 160
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 104
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2923
telemt_me_writer_restored_same_endpoint_total 2873
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 40983
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 920066176 (877.44 MB)
telemt_user_octets_to_client{user="hello"} 25635132044 (23.87 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 12257.9 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23654
telemt_connections_bad_total 2350
telemt_handshake_timeouts_total 386
telemt_upstream_connect_attempt_total 3919
telemt_upstream_connect_success_total 3774
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 3919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 81
telemt_me_reconnect_attempts_total 13257
telemt_me_reconnect_success_total 3127
telemt_me_reader_eof_total 3436
telemt_me_idle_close_by_peer_total 3436
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 7041
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20243
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 315
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 3458
telemt_me_refill_failed_total 316
telemt_me_writer_restored_same_endpoint_total 3111
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 331
telemt_user_connections_total{user="hello"} 20240
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 121770604 (116.13 MB)
telemt_user_octets_to_client{user="hello"} 5430101416 (5.06 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 12244.9 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62351
telemt_connections_bad_total 578
telemt_handshake_timeouts_total 713
telemt_upstream_connect_attempt_total 2419
telemt_upstream_connect_success_total 2407
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1239
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 1783
telemt_me_reconnect_success_total 1769
telemt_me_reader_eof_total 1858
telemt_me_idle_close_by_peer_total 1858
telemt_me_route_drop_no_conn_total 27006
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58806
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 148
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1790
telemt_me_writer_restored_same_endpoint_total 1762
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 58769
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 1927747128 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 32897658260 (30.64 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 53
```