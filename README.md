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

# Server Metrics 2026-03-15 08:00:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 35137.8 (9h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117438
telemt_connections_bad_total 935
telemt_handshake_timeouts_total 2647
telemt_upstream_connect_attempt_total 8472
telemt_upstream_connect_success_total 8422
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 8472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4621
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 6707
telemt_me_reconnect_success_total 6682
telemt_me_reader_eof_total 7153
telemt_me_idle_close_by_peer_total 7153
telemt_me_route_drop_no_conn_total 192915
telemt_me_route_drop_channel_closed_total 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136924
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 912
telemt_desync_full_logged_total 392
telemt_desync_suppressed_total 520
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 378
telemt_desync_frames_bucket_total{bucket="gt_10"} 381
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6743
telemt_me_writer_restored_same_endpoint_total 6651
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 109431
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 1582363680 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 95886398424 (89.30 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 35145.2 (9h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37032
telemt_connections_bad_total 250
telemt_handshake_timeouts_total 1204
telemt_upstream_connect_attempt_total 9306
telemt_upstream_connect_success_total 9306
telemt_upstream_connect_attempts_per_request{bucket="1"} 9306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5223
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7581
telemt_me_reconnect_success_total 7547
telemt_me_reader_eof_total 8114
telemt_me_idle_close_by_peer_total 8114
telemt_me_route_drop_no_conn_total 19281
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34212
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7622
telemt_me_writer_restored_same_endpoint_total 7531
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 34215
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 818332228 (780.42 MB)
telemt_user_octets_to_client{user="hello"} 12850586076 (11.97 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 35138.1 (9h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46971
telemt_connections_bad_total 479
telemt_handshake_timeouts_total 1882
telemt_upstream_connect_attempt_total 9256
telemt_upstream_connect_success_total 9255
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7536
telemt_me_reconnect_success_total 7501
telemt_me_reader_eof_total 8114
telemt_me_idle_close_by_peer_total 8114
telemt_me_route_drop_no_conn_total 16088
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42528
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7570
telemt_me_writer_restored_same_endpoint_total 7497
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 42466
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 8887555612 (8.28 GB)
telemt_user_octets_to_client{user="hello"} 22999220712 (21.42 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 35137.6 (9h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55192
telemt_connections_bad_total 153
telemt_handshake_timeouts_total 374
telemt_upstream_connect_attempt_total 8226
telemt_upstream_connect_success_total 8225
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6513
telemt_me_reconnect_success_total 6487
telemt_me_reader_eof_total 6939
telemt_me_idle_close_by_peer_total 6939
telemt_me_route_drop_no_conn_total 24209
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49940
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 67
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6557
telemt_me_writer_restored_same_endpoint_total 6476
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 49874
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 933970328 (890.70 MB)
telemt_user_octets_to_client{user="hello"} 29977298272 (27.92 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 10209.0 (2h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15322
telemt_connections_bad_total 1963
telemt_handshake_timeouts_total 168
telemt_upstream_connect_attempt_total 3822
telemt_upstream_connect_success_total 3784
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 3822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 97479
telemt_me_reconnect_success_total 3079
telemt_me_reader_eof_total 3154
telemt_me_idle_close_by_peer_total 3154
telemt_me_route_drop_no_conn_total 4495
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12734
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 3027
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 2975
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 12874
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 95243185 (90.83 MB)
telemt_user_octets_to_client{user="hello"} 9066870619 (8.44 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 35137.0 (9h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149403
telemt_connections_bad_total 19734
telemt_handshake_timeouts_total 724
telemt_upstream_connect_attempt_total 7555
telemt_upstream_connect_success_total 7510
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 7555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3720
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 5793
telemt_me_reconnect_success_total 5765
telemt_me_reader_eof_total 6146
telemt_me_idle_close_by_peer_total 6146
telemt_me_route_drop_no_conn_total 70814
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124979
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5795
telemt_me_writer_restored_same_endpoint_total 5738
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 123516
telemt_user_connections_current{user="hello"} 334
telemt_user_octets_from_client{user="hello"} 3439106352 (3.20 GB)
telemt_user_octets_to_client{user="hello"} 66838084720 (62.25 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 50
```