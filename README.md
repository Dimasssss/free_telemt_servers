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

# Server Metrics 2026-03-16 23:27:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 16904.1 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103764
telemt_connections_bad_total 1592
telemt_handshake_timeouts_total 4492
telemt_upstream_connect_attempt_total 3427
telemt_upstream_connect_success_total 3405
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1879
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2559
telemt_me_reconnect_success_total 2549
telemt_me_reader_eof_total 2682
telemt_me_idle_close_by_peer_total 2682
telemt_me_route_drop_no_conn_total 32791
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93355
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 537
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 385
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 244
telemt_desync_frames_bucket_total{bucket="gt_10"} 170
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2564
telemt_me_writer_restored_same_endpoint_total 2528
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 93310
telemt_user_connections_current{user="hello"} 348
telemt_user_octets_from_client{user="hello"} 1518243164 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 50324375336 (46.87 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 17155.5 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67329
telemt_connections_bad_total 846
telemt_handshake_timeouts_total 2769
telemt_upstream_connect_attempt_total 3895
telemt_upstream_connect_success_total 3844
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 3894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 2990
telemt_me_reconnect_success_total 2983
telemt_me_reader_eof_total 3137
telemt_me_idle_close_by_peer_total 3137
telemt_me_route_drop_no_conn_total 26986
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60860
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 114
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3022
telemt_me_writer_restored_same_endpoint_total 2967
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 60809
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 870632496 (830.30 MB)
telemt_user_octets_to_client{user="hello"} 27976856660 (26.06 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 16931.7 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36768
telemt_connections_bad_total 424
telemt_handshake_timeouts_total 889
telemt_upstream_connect_attempt_total 4307
telemt_upstream_connect_success_total 4279
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3442
telemt_me_reconnect_success_total 3418
telemt_me_reader_eof_total 3639
telemt_me_idle_close_by_peer_total 3639
telemt_me_route_drop_no_conn_total 12694
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34541
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3455
telemt_me_writer_restored_same_endpoint_total 3407
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 34537
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 634455964 (605.06 MB)
telemt_user_octets_to_client{user="hello"} 13817346340 (12.87 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 16990.9 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67369
telemt_connections_bad_total 3002
telemt_handshake_timeouts_total 446
telemt_upstream_connect_attempt_total 3710
telemt_upstream_connect_success_total 3668
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 3710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1921
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_reconnect_attempts_total 2832
telemt_me_reconnect_success_total 2806
telemt_me_reader_eof_total 2952
telemt_me_idle_close_by_peer_total 2952
telemt_me_route_drop_no_conn_total 22023
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62054
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2839
telemt_me_writer_restored_same_endpoint_total 2799
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 62039
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 795701220 (758.84 MB)
telemt_user_octets_to_client{user="hello"} 27621585532 (25.72 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 16962.9 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48515
telemt_connections_bad_total 13598
telemt_handshake_timeouts_total 203
telemt_upstream_connect_attempt_total 4608
telemt_upstream_connect_success_total 4538
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 4608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_reconnect_attempts_total 4798
telemt_me_reconnect_success_total 3685
telemt_me_reader_eof_total 3848
telemt_me_idle_close_by_peer_total 3848
telemt_me_route_drop_no_conn_total 12959
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33226
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3791
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 3677
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 33222
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 264410360 (252.16 MB)
telemt_user_octets_to_client{user="hello"} 12818286748 (11.94 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 17124.1 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110381
telemt_connections_bad_total 1172
telemt_handshake_timeouts_total 895
telemt_upstream_connect_attempt_total 3370
telemt_upstream_connect_success_total 3349
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 2506
telemt_me_reconnect_success_total 2501
telemt_me_reader_eof_total 2656
telemt_me_idle_close_by_peer_total 2656
telemt_me_route_drop_no_conn_total 110033
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150695
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2539
telemt_me_writer_restored_same_endpoint_total 2491
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 104467
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 1938568512 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 73109580908 (68.09 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 5130.4 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92
telemt_connections_bad_total 55
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2254
telemt_upstream_connect_success_total 2254
telemt_upstream_connect_attempts_per_request{bucket="1"} 2254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 931
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1971
telemt_me_reconnect_success_total 1962
telemt_me_reader_eof_total 2132
telemt_me_idle_close_by_peer_total 2132
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1977
telemt_me_writer_restored_same_endpoint_total 1962
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```