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

# Server Metrics 2026-03-15 01:49:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 12886.1 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27035
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 273
telemt_upstream_connect_attempt_total 3305
telemt_upstream_connect_success_total 3284
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1778
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 2617
telemt_me_reconnect_success_total 2604
telemt_me_reader_eof_total 2758
telemt_me_idle_close_by_peer_total 2758
telemt_me_route_drop_no_conn_total 7805
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25568
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 135
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2609
telemt_me_writer_restored_same_endpoint_total 2573
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 25566
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 274681124 (261.96 MB)
telemt_user_octets_to_client{user="hello"} 10036878764 (9.35 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 12892.5 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12274
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 3588
telemt_upstream_connect_success_total 3588
telemt_upstream_connect_attempts_per_request{bucket="1"} 3588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2916
telemt_me_reconnect_success_total 2905
telemt_me_reader_eof_total 3097
telemt_me_idle_close_by_peer_total 3097
telemt_me_route_drop_no_conn_total 4337
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11591
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2922
telemt_me_writer_restored_same_endpoint_total 2889
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 11595
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 317420116 (302.72 MB)
telemt_user_octets_to_client{user="hello"} 2023340320 (1.88 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 12885.0 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12487
telemt_connections_bad_total 130
telemt_handshake_timeouts_total 233
telemt_upstream_connect_attempt_total 3456
telemt_upstream_connect_success_total 3455
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1914
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2787
telemt_me_reconnect_success_total 2773
telemt_me_reader_eof_total 2986
telemt_me_idle_close_by_peer_total 2986
telemt_me_route_drop_no_conn_total 4288
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11736
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2790
telemt_me_writer_restored_same_endpoint_total 2769
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 11695
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 8457185892 (7.88 GB)
telemt_user_octets_to_client{user="hello"} 13350134280 (12.43 GB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 12885.0 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13355
telemt_connections_bad_total 78
telemt_handshake_timeouts_total 43
telemt_upstream_connect_attempt_total 3127
telemt_upstream_connect_success_total 3126
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2462
telemt_me_reconnect_success_total 2450
telemt_me_reader_eof_total 2603
telemt_me_idle_close_by_peer_total 2603
telemt_me_route_drop_no_conn_total 5226
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12707
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2470
telemt_me_writer_restored_same_endpoint_total 2439
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 12705
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 360157512 (343.47 MB)
telemt_user_octets_to_client{user="hello"} 9519450984 (8.87 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 12884.9 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15985
telemt_connections_bad_total 2607
telemt_handshake_timeouts_total 388
telemt_upstream_connect_attempt_total 4181
telemt_upstream_connect_success_total 4128
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 4181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2216
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 3528
telemt_me_reconnect_success_total 3449
telemt_me_reader_eof_total 3633
telemt_me_idle_close_by_peer_total 3633
telemt_me_route_drop_no_conn_total 4502
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12684
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 3460
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 3437
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 12670
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 182713892 (174.25 MB)
telemt_user_octets_to_client{user="hello"} 6680448192 (6.22 GB)
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 12884.0 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40904
telemt_connections_bad_total 1075
telemt_handshake_timeouts_total 164
telemt_upstream_connect_attempt_total 2845
telemt_upstream_connect_success_total 2827
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1413
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2158
telemt_me_reconnect_success_total 2151
telemt_me_reader_eof_total 2261
telemt_me_idle_close_by_peer_total 2261
telemt_me_route_drop_no_conn_total 22711
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40034
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2143
telemt_me_writer_restored_same_endpoint_total 2124
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 38603
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 1416947280 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 25570639328 (23.81 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 32
```