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

# Server Metrics 2026-03-12 11:06:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 12763.2 (3h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66876
telemt_connections_bad_total 494
telemt_handshake_timeouts_total 2594
telemt_upstream_connect_attempt_total 3154
telemt_upstream_connect_success_total 3141
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 2465
telemt_me_reconnect_success_total 2451
telemt_me_reader_eof_total 2546
telemt_me_idle_close_by_peer_total 2545
telemt_me_route_drop_no_conn_total 18301
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60401
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 246
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2463
telemt_me_writer_restored_same_endpoint_total 2435
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 60381
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 892117476 (850.79 MB)
telemt_user_octets_to_client{user="hello"} 18351489944 (17.09 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 12656.3 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26908
telemt_connections_bad_total 219
telemt_handshake_timeouts_total 196
telemt_upstream_connect_attempt_total 4497
telemt_upstream_connect_success_total 4408
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 4497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 10003
telemt_me_reconnect_success_total 3750
telemt_me_reader_eof_total 3989
telemt_me_idle_close_by_peer_total 3989
telemt_me_route_drop_no_conn_total 10639
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25614
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 3959
telemt_me_refill_failed_total 195
telemt_me_writer_restored_same_endpoint_total 3735
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 25615
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 265506204 (253.21 MB)
telemt_user_octets_to_client{user="hello"} 5667083940 (5.28 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 12619.8 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38070
telemt_connections_bad_total 103
telemt_handshake_timeouts_total 305
telemt_upstream_connect_attempt_total 3487
telemt_upstream_connect_success_total 3487
telemt_upstream_connect_attempts_per_request{bucket="1"} 3487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1761
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2849
telemt_me_reconnect_success_total 2831
telemt_me_reader_eof_total 2956
telemt_me_idle_close_by_peer_total 2956
telemt_me_route_drop_no_conn_total 12278
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35645
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
telemt_me_writer_removed_unexpected_total 2834
telemt_me_writer_restored_same_endpoint_total 2811
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 35633
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 474976268 (452.97 MB)
telemt_user_octets_to_client{user="hello"} 29576592060 (27.55 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 12595.5 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46245
telemt_connections_bad_total 1035
telemt_handshake_timeouts_total 242
telemt_upstream_connect_attempt_total 3707
telemt_upstream_connect_success_total 3625
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 3707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2088
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 160
telemt_me_reconnect_attempts_total 3013
telemt_me_reconnect_success_total 2974
telemt_me_reader_eof_total 3085
telemt_me_idle_close_by_peer_total 3085
telemt_me_route_drop_no_conn_total 14414
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42077
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 161
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 104
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3016
telemt_me_writer_restored_same_endpoint_total 2966
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 42076
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 926211772 (883.30 MB)
telemt_user_octets_to_client{user="hello"} 25920070628 (24.14 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 12565.0 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24328
telemt_connections_bad_total 2404
telemt_handshake_timeouts_total 389
telemt_upstream_connect_attempt_total 3972
telemt_upstream_connect_success_total 3827
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 3972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 13310
telemt_me_reconnect_success_total 3180
telemt_me_reader_eof_total 3489
telemt_me_idle_close_by_peer_total 3489
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 7212
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20842
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 325
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 228
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 3511
telemt_me_refill_failed_total 316
telemt_me_writer_restored_same_endpoint_total 3164
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 331
telemt_user_connections_total{user="hello"} 20840
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 126064480 (120.22 MB)
telemt_user_octets_to_client{user="hello"} 5550362600 (5.17 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 12552.0 (3h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64587
telemt_connections_bad_total 578
telemt_handshake_timeouts_total 717
telemt_upstream_connect_attempt_total 2447
telemt_upstream_connect_success_total 2435
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 1811
telemt_me_reconnect_success_total 1797
telemt_me_reader_eof_total 1886
telemt_me_idle_close_by_peer_total 1886
telemt_me_route_drop_no_conn_total 27785
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60988
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 152
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1818
telemt_me_writer_restored_same_endpoint_total 1790
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 60951
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 1951360404 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 33618936232 (31.31 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 59
```