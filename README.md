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

# Server Metrics 2026-03-12 09:23:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 6624.5 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35863
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 2064
telemt_upstream_connect_attempt_total 1459
telemt_upstream_connect_success_total 1453
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 776
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 43
telemt_me_reconnect_attempts_total 1084
telemt_me_reconnect_success_total 1078
telemt_me_reader_eof_total 1095
telemt_me_idle_close_by_peer_total 1095
telemt_me_route_drop_no_conn_total 9406
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31566
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 95
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 53
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1075
telemt_me_writer_restored_same_endpoint_total 1062
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_user_connections_total{user="hello"} 31562
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 444117924 (423.54 MB)
telemt_user_octets_to_client{user="hello"} 9318381904 (8.68 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 6517.8 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13945
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 118
telemt_upstream_connect_attempt_total 2345
telemt_upstream_connect_success_total 2296
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 2345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1536
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 4713
telemt_me_reconnect_success_total 1925
telemt_me_reader_eof_total 2004
telemt_me_idle_close_by_peer_total 2004
telemt_me_route_drop_no_conn_total 4958
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13311
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 2004
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1910
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 13307
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 77377684 (73.79 MB)
telemt_user_octets_to_client{user="hello"} 2373746884 (2.21 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 6481.9 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20196
telemt_connections_bad_total 62
telemt_handshake_timeouts_total 145
telemt_upstream_connect_attempt_total 1699
telemt_upstream_connect_success_total 1699
telemt_upstream_connect_attempts_per_request{bucket="1"} 1699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 874
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 1330
telemt_me_reconnect_success_total 1323
telemt_me_reader_eof_total 1373
telemt_me_idle_close_by_peer_total 1373
telemt_me_route_drop_no_conn_total 6659
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18786
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1307
telemt_me_writer_restored_same_endpoint_total 1303
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 18782
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 206327416 (196.77 MB)
telemt_user_octets_to_client{user="hello"} 19418763868 (18.09 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 6457.1 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22841
telemt_connections_bad_total 1023
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 1859
telemt_upstream_connect_success_total 1807
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 1859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1034
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 1455
telemt_me_reconnect_success_total 1427
telemt_me_reader_eof_total 1475
telemt_me_idle_close_by_peer_total 1475
telemt_me_route_drop_no_conn_total 6680
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20229
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 88
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1448
telemt_me_writer_restored_same_endpoint_total 1419
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 20228
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 593894280 (566.38 MB)
telemt_user_octets_to_client{user="hello"} 7204314424 (6.71 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 6426.4 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12314
telemt_connections_bad_total 1269
telemt_handshake_timeouts_total 168
telemt_upstream_connect_attempt_total 1989
telemt_upstream_connect_success_total 1901
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 1989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1239
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 6723
telemt_me_reconnect_success_total 1532
telemt_me_reader_eof_total 1672
telemt_me_idle_close_by_peer_total 1672
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 3499
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10617
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 189
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 165
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_me_writer_removed_unexpected_total 1695
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 1519
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 10616
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 46729620 (44.56 MB)
telemt_user_octets_to_client{user="hello"} 2677906432 (2.49 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 6413.4 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30781
telemt_connections_bad_total 528
telemt_handshake_timeouts_total 473
telemt_upstream_connect_attempt_total 1143
telemt_upstream_connect_success_total 1135
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 578
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 772
telemt_me_reconnect_success_total 765
telemt_me_reader_eof_total 792
telemt_me_idle_close_by_peer_total 792
telemt_me_route_drop_no_conn_total 13695
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28686
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 776
telemt_me_writer_restored_same_endpoint_total 758
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 28653
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 1522044864 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 19124165648 (17.81 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 51
```