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

# Server Metrics 2026-03-14 15:01:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 6299.4 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37164
telemt_connections_bad_total 6886
telemt_handshake_timeouts_total 202
telemt_upstream_connect_attempt_total 1672
telemt_upstream_connect_success_total 1671
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 1338
telemt_me_reconnect_success_total 1318
telemt_me_reader_eof_total 1343
telemt_me_idle_close_by_peer_total 1343
telemt_me_route_drop_no_conn_total 14050
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29330
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 37
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1346
telemt_me_writer_restored_same_endpoint_total 1300
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 29267
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 448692452 (427.91 MB)
telemt_user_octets_to_client{user="hello"} 10734373492 (10.00 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 6297.6 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14744
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 481
telemt_upstream_connect_attempt_total 1831
telemt_upstream_connect_success_total 1806
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 1831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1076
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 2704
telemt_me_reconnect_success_total 1460
telemt_me_reader_eof_total 1520
telemt_me_idle_close_by_peer_total 1520
telemt_me_route_drop_no_conn_total 7905
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13759
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1519
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 1455
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 13742
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 173147744 (165.13 MB)
telemt_user_octets_to_client{user="hello"} 3979308828 (3.71 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 6302.2 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14273
telemt_connections_bad_total 64
telemt_handshake_timeouts_total 234
telemt_upstream_connect_attempt_total 2992
telemt_upstream_connect_success_total 2970
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1495
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 96184
telemt_me_reconnect_success_total 2308
telemt_me_reader_eof_total 2423
telemt_me_idle_close_by_peer_total 2423
telemt_me_route_drop_no_conn_total 5414
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12829
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 2427
telemt_me_refill_failed_total 3045
telemt_me_writer_restored_same_endpoint_total 2270
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 13127
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 483657201 (461.25 MB)
telemt_user_octets_to_client{user="hello"} 6330047706 (5.90 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 6306.9 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19800
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 149
telemt_upstream_connect_attempt_total 1594
telemt_upstream_connect_success_total 1588
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 36
telemt_me_reconnect_attempts_total 1256
telemt_me_reconnect_success_total 1247
telemt_me_reader_eof_total 1276
telemt_me_idle_close_by_peer_total 1276
telemt_me_route_drop_no_conn_total 9763
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18776
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 186
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1252
telemt_me_writer_restored_same_endpoint_total 1245
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 18659
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 223169452 (212.83 MB)
telemt_user_octets_to_client{user="hello"} 6459549708 (6.02 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 6300.0 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14153
telemt_connections_bad_total 1311
telemt_handshake_timeouts_total 163
telemt_upstream_connect_attempt_total 1449
telemt_upstream_connect_success_total 1426
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 1449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 851
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 6210
telemt_me_reconnect_success_total 1080
telemt_me_reader_eof_total 1217
telemt_me_idle_close_by_peer_total 1217
telemt_me_route_drop_no_conn_total 4980
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11908
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 58
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_me_writer_removed_unexpected_total 1237
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 1076
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 11904
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 103588892 (98.79 MB)
telemt_user_octets_to_client{user="hello"} 3189125460 (2.97 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 6299.5 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50121
telemt_connections_bad_total 154
telemt_handshake_timeouts_total 367
telemt_upstream_connect_attempt_total 1325
telemt_upstream_connect_success_total 1293
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 1325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 613
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 974
telemt_me_reconnect_success_total 947
telemt_me_reader_eof_total 960
telemt_me_idle_close_by_peer_total 960
telemt_me_route_drop_no_conn_total 25426
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46213
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 950
telemt_me_writer_restored_same_endpoint_total 943
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 46121
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 773846156 (738.00 MB)
telemt_user_octets_to_client{user="hello"} 17322848352 (16.13 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 67
```