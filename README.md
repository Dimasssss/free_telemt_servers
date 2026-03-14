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

# Server Metrics 2026-03-14 15:21:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 7525.5 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43530
telemt_connections_bad_total 7961
telemt_handshake_timeouts_total 229
telemt_upstream_connect_attempt_total 2001
telemt_upstream_connect_success_total 1999
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 966
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 1579
telemt_me_reconnect_success_total 1557
telemt_me_reader_eof_total 1619
telemt_me_idle_close_by_peer_total 1619
telemt_me_route_drop_no_conn_total 16928
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34352
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 43
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1591
telemt_me_writer_restored_same_endpoint_total 1539
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 34288
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 587129760 (559.93 MB)
telemt_user_octets_to_client{user="hello"} 12350739712 (11.50 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 7523.9 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17293
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 496
telemt_upstream_connect_attempt_total 2179
telemt_upstream_connect_success_total 2152
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 2179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 4274
telemt_me_reconnect_success_total 1718
telemt_me_reader_eof_total 1838
telemt_me_idle_close_by_peer_total 1838
telemt_me_route_drop_no_conn_total 9277
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16193
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1822
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1713
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 16176
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 208372300 (198.72 MB)
telemt_user_octets_to_client{user="hello"} 4823777748 (4.49 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 7528.1 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16960
telemt_connections_bad_total 132
telemt_handshake_timeouts_total 363
telemt_upstream_connect_attempt_total 3446
telemt_upstream_connect_success_total 3418
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 3446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1706
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 96543
telemt_me_reconnect_success_total 2664
telemt_me_reader_eof_total 2800
telemt_me_idle_close_by_peer_total 2800
telemt_me_route_drop_no_conn_total 6685
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15221
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
telemt_me_writer_removed_unexpected_total 2786
telemt_me_refill_failed_total 3045
telemt_me_writer_restored_same_endpoint_total 2626
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 15514
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 507279841 (483.78 MB)
telemt_user_octets_to_client{user="hello"} 7179622634 (6.69 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 7533.1 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23903
telemt_connections_bad_total 75
telemt_handshake_timeouts_total 173
telemt_upstream_connect_attempt_total 2042
telemt_upstream_connect_success_total 2032
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1096
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 1610
telemt_me_reconnect_success_total 1597
telemt_me_reader_eof_total 1630
telemt_me_idle_close_by_peer_total 1630
telemt_me_route_drop_no_conn_total 11502
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22699
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 279
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1606
telemt_me_writer_restored_same_endpoint_total 1595
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 22582
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 254974600 (243.16 MB)
telemt_user_octets_to_client{user="hello"} 8640190152 (8.05 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 7526.2 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16661
telemt_connections_bad_total 1542
telemt_handshake_timeouts_total 229
telemt_upstream_connect_attempt_total 1682
telemt_upstream_connect_success_total 1655
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 1682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 993
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 7725
telemt_me_reconnect_success_total 1218
telemt_me_reader_eof_total 1402
telemt_me_idle_close_by_peer_total 1402
telemt_me_route_drop_no_conn_total 5903
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14040
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 55
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1418
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 1214
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 14036
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 116152308 (110.77 MB)
telemt_user_octets_to_client{user="hello"} 3691028668 (3.44 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 7525.9 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59737
telemt_connections_bad_total 183
telemt_handshake_timeouts_total 425
telemt_upstream_connect_attempt_total 1670
telemt_upstream_connect_success_total 1631
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 1669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 785
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1222
telemt_me_reconnect_success_total 1191
telemt_me_reader_eof_total 1212
telemt_me_idle_close_by_peer_total 1212
telemt_me_route_drop_no_conn_total 30084
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55287
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
telemt_me_writer_removed_unexpected_total 1203
telemt_me_writer_restored_same_endpoint_total 1187
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 55193
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 897866268 (856.27 MB)
telemt_user_octets_to_client{user="hello"} 21551678448 (20.07 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 68
```