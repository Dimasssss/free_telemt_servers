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

# Server Metrics 2026-03-16 16:45:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 11266.3 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119505
telemt_connections_bad_total 614
telemt_handshake_timeouts_total 3721
telemt_upstream_connect_attempt_total 2476
telemt_upstream_connect_success_total 2467
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1270
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3011
telemt_me_reconnect_success_total 1841
telemt_me_reader_eof_total 1907
telemt_me_idle_close_by_peer_total 1907
telemt_me_route_drop_no_conn_total 36122
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111247
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 590
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 206
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1887
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1839
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 111167
telemt_user_connections_current{user="hello"} 722
telemt_user_octets_from_client{user="hello"} 1996292116 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 63997814944 (59.60 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 6044.1 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42759
telemt_connections_bad_total 410
telemt_handshake_timeouts_total 1391
telemt_upstream_connect_attempt_total 1367
telemt_upstream_connect_success_total 1357
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 742
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 3200
telemt_me_reconnect_success_total 1007
telemt_me_reader_eof_total 1076
telemt_me_idle_close_by_peer_total 1076
telemt_me_route_drop_no_conn_total 27473
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39588
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 51
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 38
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1095
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 1002
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 39549
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 445531876 (424.89 MB)
telemt_user_octets_to_client{user="hello"} 12211002576 (11.37 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 11378.9 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47079
telemt_connections_bad_total 60
telemt_handshake_timeouts_total 727
telemt_upstream_connect_attempt_total 3292
telemt_upstream_connect_success_total 3251
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 3292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 39407
telemt_me_reconnect_success_total 1648
telemt_me_reader_eof_total 1911
telemt_me_idle_close_by_peer_total 1911
telemt_me_route_drop_no_conn_total 16315
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42817
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 98
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1936
telemt_me_refill_failed_total 1179
telemt_me_writer_restored_same_endpoint_total 1604
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 43760
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 532630958 (507.96 MB)
telemt_user_octets_to_client{user="hello"} 10111786658 (9.42 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 11515.1 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90666
telemt_connections_bad_total 158
telemt_handshake_timeouts_total 1636
telemt_upstream_connect_attempt_total 2428
telemt_upstream_connect_success_total 2410
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 8104
telemt_me_reconnect_success_total 1757
telemt_me_reader_eof_total 1975
telemt_me_idle_close_by_peer_total 1975
telemt_me_route_drop_no_conn_total 35269
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85653
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 501
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 371
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 217
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1975
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 1753
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 85631
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 1240702736 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 22301709088 (20.77 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 8975.6 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53317
telemt_connections_bad_total 18541
telemt_handshake_timeouts_total 411
telemt_upstream_connect_attempt_total 2182
telemt_upstream_connect_success_total 2153
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 2335
telemt_me_reconnect_success_total 1676
telemt_me_reader_eof_total 1734
telemt_me_idle_close_by_peer_total 1734
telemt_me_route_drop_no_conn_total 45271
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51541
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 43
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1722
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1676
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 32595
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 1917511740 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 26128666496 (24.33 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 11083.3 (3h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129014
telemt_connections_bad_total 1233
telemt_handshake_timeouts_total 2990
telemt_upstream_connect_attempt_total 2453
telemt_upstream_connect_success_total 2453
telemt_upstream_connect_attempts_per_request{bucket="1"} 2453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1259
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 6851
telemt_me_reconnect_success_total 1828
telemt_me_reader_eof_total 1997
telemt_me_idle_close_by_peer_total 1997
telemt_me_route_drop_no_conn_total 59548
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120013
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 36
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1997
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 1823
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 119731
telemt_user_connections_current{user="hello"} 762
telemt_user_octets_from_client{user="hello"} 2381494584 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 43592706108 (40.60 GB)
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 118
```