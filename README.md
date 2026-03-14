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

# Server Metrics 2026-03-14 15:42:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 8751.7 (2h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49460
telemt_connections_bad_total 8258
telemt_handshake_timeouts_total 243
telemt_upstream_connect_attempt_total 2261
telemt_upstream_connect_success_total 2259
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1117
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 1796
telemt_me_reconnect_success_total 1773
telemt_me_reader_eof_total 1849
telemt_me_idle_close_by_peer_total 1849
telemt_me_route_drop_no_conn_total 19176
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39748
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 95
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1810
telemt_me_writer_restored_same_endpoint_total 1755
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 39684
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 687730228 (655.87 MB)
telemt_user_octets_to_client{user="hello"} 14042610308 (13.08 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 8749.9 (2h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19923
telemt_connections_bad_total 40
telemt_handshake_timeouts_total 500
telemt_upstream_connect_attempt_total 2439
telemt_upstream_connect_success_total 2412
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 2439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 4491
telemt_me_reconnect_success_total 1934
telemt_me_reader_eof_total 2068
telemt_me_idle_close_by_peer_total 2068
telemt_me_route_drop_no_conn_total 10502
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18709
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
telemt_me_writer_removed_unexpected_total 2041
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1929
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 18692
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 251497112 (239.85 MB)
telemt_user_octets_to_client{user="hello"} 7442330544 (6.93 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 8754.2 (2h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19794
telemt_connections_bad_total 214
telemt_handshake_timeouts_total 839
telemt_upstream_connect_attempt_total 3811
telemt_upstream_connect_success_total 3778
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 3811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 96860
telemt_me_reconnect_success_total 2980
telemt_me_reader_eof_total 3118
telemt_me_idle_close_by_peer_total 3118
telemt_me_route_drop_no_conn_total 7731
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17373
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 3104
telemt_me_refill_failed_total 3045
telemt_me_writer_restored_same_endpoint_total 2942
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 17666
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 539470505 (514.48 MB)
telemt_user_octets_to_client{user="hello"} 8201381998 (7.64 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 8759.2 (2h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27913
telemt_connections_bad_total 77
telemt_handshake_timeouts_total 190
telemt_upstream_connect_attempt_total 2421
telemt_upstream_connect_success_total 2406
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 2421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1309
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 1941
telemt_me_reconnect_success_total 1928
telemt_me_reader_eof_total 1989
telemt_me_idle_close_by_peer_total 1989
telemt_me_route_drop_no_conn_total 13310
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26536
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 228
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 137
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1939
telemt_me_writer_restored_same_endpoint_total 1926
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 26418
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 322434928 (307.50 MB)
telemt_user_octets_to_client{user="hello"} 10258818784 (9.55 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 8752.2 (2h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19529
telemt_connections_bad_total 1762
telemt_handshake_timeouts_total 733
telemt_upstream_connect_attempt_total 1949
telemt_upstream_connect_success_total 1920
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 1949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 7947
telemt_me_reconnect_success_total 1439
telemt_me_reader_eof_total 1632
telemt_me_idle_close_by_peer_total 1632
telemt_me_route_drop_no_conn_total 6904
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16098
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
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1641
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 1435
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 16094
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 134979204 (128.73 MB)
telemt_user_octets_to_client{user="hello"} 3951138184 (3.68 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 8751.9 (2h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68298
telemt_connections_bad_total 201
telemt_handshake_timeouts_total 472
telemt_upstream_connect_attempt_total 1992
telemt_upstream_connect_success_total 1951
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 1992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 979
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 2489
telemt_me_reconnect_success_total 1465
telemt_me_reader_eof_total 1519
telemt_me_idle_close_by_peer_total 1519
telemt_me_route_drop_no_conn_total 34442
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63354
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1510
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 1461
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 63258
telemt_user_connections_current{user="hello"} 478
telemt_user_octets_from_client{user="hello"} 1053947844 (1005.12 MB)
telemt_user_octets_to_client{user="hello"} 24289719992 (22.62 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 70
```