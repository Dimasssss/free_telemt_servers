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

# Server Metrics 2026-03-16 16:55:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 11877.6 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125124
telemt_connections_bad_total 618
telemt_handshake_timeouts_total 3743
telemt_upstream_connect_attempt_total 2590
telemt_upstream_connect_success_total 2580
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3079
telemt_me_reconnect_success_total 1909
telemt_me_reader_eof_total 1975
telemt_me_idle_close_by_peer_total 1975
telemt_me_route_drop_no_conn_total 37657
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116680
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 615
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 475
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1955
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1907
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 116600
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 2137434604 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 67378367380 (62.75 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 6655.9 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46356
telemt_connections_bad_total 411
telemt_handshake_timeouts_total 1399
telemt_upstream_connect_attempt_total 1497
telemt_upstream_connect_success_total 1486
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 4596
telemt_me_reconnect_success_total 1091
telemt_me_reader_eof_total 1201
telemt_me_idle_close_by_peer_total 1201
telemt_me_route_drop_no_conn_total 29502
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43086
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 72
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1220
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 1086
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 43044
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 572520324 (546.00 MB)
telemt_user_octets_to_client{user="hello"} 13636914208 (12.70 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 11990.7 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48992
telemt_connections_bad_total 60
telemt_handshake_timeouts_total 777
telemt_upstream_connect_attempt_total 3505
telemt_upstream_connect_success_total 3462
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 3505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 39575
telemt_me_reconnect_success_total 1814
telemt_me_reader_eof_total 2101
telemt_me_idle_close_by_peer_total 2101
telemt_me_route_drop_no_conn_total 17147
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44566
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 124
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2104
telemt_me_refill_failed_total 1179
telemt_me_writer_restored_same_endpoint_total 1770
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 45508
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 567019182 (540.75 MB)
telemt_user_octets_to_client{user="hello"} 10853633722 (10.11 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 12127.0 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95141
telemt_connections_bad_total 186
telemt_handshake_timeouts_total 1691
telemt_upstream_connect_attempt_total 2594
telemt_upstream_connect_success_total 2573
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 2594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1325
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 8224
telemt_me_reconnect_success_total 1874
telemt_me_reader_eof_total 2094
telemt_me_idle_close_by_peer_total 2094
telemt_me_route_drop_no_conn_total 36513
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89902
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 520
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 383
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2094
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 1870
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 220
telemt_user_connections_total{user="hello"} 89879
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 1290742032 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 23558358120 (21.94 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 9587.4 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56021
telemt_connections_bad_total 18984
telemt_handshake_timeouts_total 457
telemt_upstream_connect_attempt_total 2413
telemt_upstream_connect_success_total 2382
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 2413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_reconnect_attempts_total 2519
telemt_me_reconnect_success_total 1859
telemt_me_reader_eof_total 1922
telemt_me_idle_close_by_peer_total 1922
telemt_me_route_drop_no_conn_total 46243
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53659
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 51
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1910
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1859
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 34712
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 1933825396 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 26987026712 (25.13 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 11694.7 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136830
telemt_connections_bad_total 1533
telemt_handshake_timeouts_total 3015
telemt_upstream_connect_attempt_total 2559
telemt_upstream_connect_success_total 2559
telemt_upstream_connect_attempts_per_request{bucket="1"} 2559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1319
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 6957
telemt_me_reconnect_success_total 1934
telemt_me_reader_eof_total 2103
telemt_me_idle_close_by_peer_total 2103
telemt_me_route_drop_no_conn_total 62909
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 127201
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 37
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2103
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 1929
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 126918
telemt_user_connections_current{user="hello"} 774
telemt_user_octets_from_client{user="hello"} 2584048412 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 47062842760 (43.83 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 100
```