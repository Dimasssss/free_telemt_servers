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

# Server Metrics 2026-03-16 20:09:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 5064.5 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38433
telemt_connections_bad_total 337
telemt_handshake_timeouts_total 2421
telemt_upstream_connect_attempt_total 945
telemt_upstream_connect_success_total 936
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 514
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 652
telemt_me_reconnect_success_total 650
telemt_me_reader_eof_total 651
telemt_me_idle_close_by_peer_total 651
telemt_me_route_drop_no_conn_total 11892
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34171
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 192
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 155
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 645
telemt_me_writer_restored_same_endpoint_total 629
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_user_connections_total{user="hello"} 34165
telemt_user_connections_current{user="hello"} 601
telemt_user_octets_from_client{user="hello"} 616131384 (587.59 MB)
telemt_user_octets_to_client{user="hello"} 22992825268 (21.41 GB)
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 5316.2 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31879
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 1338
telemt_upstream_connect_attempt_total 1101
telemt_upstream_connect_success_total 1082
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 565
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 800
telemt_me_reconnect_success_total 799
telemt_me_reader_eof_total 804
telemt_me_idle_close_by_peer_total 804
telemt_me_route_drop_no_conn_total 13056
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28769
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 72
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 811
telemt_me_writer_restored_same_endpoint_total 783
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 28768
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 303597784 (289.53 MB)
telemt_user_octets_to_client{user="hello"} 10762672700 (10.02 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 5092.3 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16079
telemt_connections_bad_total 60
telemt_handshake_timeouts_total 123
telemt_upstream_connect_attempt_total 1099
telemt_upstream_connect_success_total 1089
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1099
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 615
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 814
telemt_me_reconnect_success_total 799
telemt_me_reader_eof_total 817
telemt_me_idle_close_by_peer_total 817
telemt_me_route_drop_no_conn_total 5256
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15513
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
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 805
telemt_me_writer_restored_same_endpoint_total 788
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 15510
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 405162604 (386.39 MB)
telemt_user_octets_to_client{user="hello"} 6772252572 (6.31 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 5151.5 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33074
telemt_connections_bad_total 1479
telemt_handshake_timeouts_total 335
telemt_upstream_connect_attempt_total 1038
telemt_upstream_connect_success_total 1024
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 741
telemt_me_reconnect_success_total 735
telemt_me_reader_eof_total 745
telemt_me_idle_close_by_peer_total 745
telemt_me_route_drop_no_conn_total 9885
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30140
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 91
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 739
telemt_me_writer_restored_same_endpoint_total 728
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 30135
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 398662588 (380.19 MB)
telemt_user_octets_to_client{user="hello"} 10804936540 (10.06 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 5123.4 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20737
telemt_connections_bad_total 5861
telemt_handshake_timeouts_total 135
telemt_upstream_connect_attempt_total 1434
telemt_upstream_connect_success_total 1412
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 1434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 702
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 2219
telemt_me_reconnect_success_total 1128
telemt_me_reader_eof_total 1149
telemt_me_idle_close_by_peer_total 1149
telemt_me_route_drop_no_conn_total 5553
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13970
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1155
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 1120
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 13968
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 107019248 (102.06 MB)
telemt_user_octets_to_client{user="hello"} 4242923120 (3.95 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 5284.6 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48855
telemt_connections_bad_total 102
telemt_handshake_timeouts_total 632
telemt_upstream_connect_attempt_total 983
telemt_upstream_connect_success_total 977
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 471
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 502
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 695
telemt_me_reconnect_success_total 694
telemt_me_reader_eof_total 711
telemt_me_idle_close_by_peer_total 711
telemt_me_route_drop_no_conn_total 19609
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46264
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 704
telemt_me_writer_restored_same_endpoint_total 684
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 46257
telemt_user_connections_current{user="hello"} 574
telemt_user_octets_from_client{user="hello"} 658986776 (628.46 MB)
telemt_user_octets_to_client{user="hello"} 25530894392 (23.78 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 55
```