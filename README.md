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

# Server Metrics 2026-03-14 15:52:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 9364.9 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54231
telemt_connections_bad_total 10564
telemt_handshake_timeouts_total 249
telemt_upstream_connect_attempt_total 2422
telemt_upstream_connect_success_total 2420
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1913
telemt_me_reconnect_success_total 1889
telemt_me_reader_eof_total 1979
telemt_me_idle_close_by_peer_total 1979
telemt_me_route_drop_no_conn_total 20391
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42131
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 122
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1928
telemt_me_writer_restored_same_endpoint_total 1871
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 42067
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 711080772 (678.14 MB)
telemt_user_octets_to_client{user="hello"} 14813673268 (13.80 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 9362.9 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21283
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 503
telemt_upstream_connect_attempt_total 2620
telemt_upstream_connect_success_total 2592
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 2620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1519
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 4627
telemt_me_reconnect_success_total 2067
telemt_me_reader_eof_total 2204
telemt_me_idle_close_by_peer_total 2204
telemt_me_route_drop_no_conn_total 11485
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20013
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2178
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 2062
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 19996
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 267117772 (254.74 MB)
telemt_user_octets_to_client{user="hello"} 8294382628 (7.72 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 9367.3 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21333
telemt_connections_bad_total 220
telemt_handshake_timeouts_total 1004
telemt_upstream_connect_attempt_total 4011
telemt_upstream_connect_success_total 3976
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 4011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1994
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 97015
telemt_me_reconnect_success_total 3134
telemt_me_reader_eof_total 3294
telemt_me_idle_close_by_peer_total 3294
telemt_me_route_drop_no_conn_total 8237
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18689
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 3260
telemt_me_refill_failed_total 3045
telemt_me_writer_restored_same_endpoint_total 3096
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 18979
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 573272545 (546.72 MB)
telemt_user_octets_to_client{user="hello"} 8942262518 (8.33 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 9372.1 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29700
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 198
telemt_upstream_connect_attempt_total 2596
telemt_upstream_connect_success_total 2581
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1392
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 2070
telemt_me_reconnect_success_total 2055
telemt_me_reader_eof_total 2118
telemt_me_idle_close_by_peer_total 2118
telemt_me_route_drop_no_conn_total 14151
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28275
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 318
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2070
telemt_me_writer_restored_same_endpoint_total 2053
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 28157
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 336008656 (320.44 MB)
telemt_user_octets_to_client{user="hello"} 10771032252 (10.03 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 9365.4 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20795
telemt_connections_bad_total 1880
telemt_handshake_timeouts_total 895
telemt_upstream_connect_attempt_total 2131
telemt_upstream_connect_success_total 2100
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 2131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 8084
telemt_me_reconnect_success_total 1572
telemt_me_reader_eof_total 1781
telemt_me_idle_close_by_peer_total 1781
telemt_me_route_drop_no_conn_total 7286
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17053
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 65
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1777
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 1568
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 17048
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 141684660 (135.12 MB)
telemt_user_octets_to_client{user="hello"} 4321158660 (4.02 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 9364.9 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72630
telemt_connections_bad_total 201
telemt_handshake_timeouts_total 554
telemt_upstream_connect_attempt_total 2139
telemt_upstream_connect_success_total 2095
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 2139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1049
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 3866
telemt_me_reconnect_success_total 1561
telemt_me_reader_eof_total 1654
telemt_me_idle_close_by_peer_total 1654
telemt_me_route_drop_no_conn_total 36871
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67415
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1647
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 1557
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 67316
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 1105229496 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 26432673588 (24.62 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 71
```