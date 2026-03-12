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

# Server Metrics 2026-03-12 08:48:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 4478.8 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24442
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 1958
telemt_upstream_connect_attempt_total 910
telemt_upstream_connect_success_total 908
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 414
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 671
telemt_me_reconnect_success_total 668
telemt_me_reader_eof_total 667
telemt_me_idle_close_by_peer_total 667
telemt_me_route_drop_no_conn_total 6075
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21161
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 66
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 663
telemt_me_writer_restored_same_endpoint_total 652
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_user_connections_total{user="hello"} 21159
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 209111476 (199.42 MB)
telemt_user_octets_to_client{user="hello"} 7187406748 (6.69 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 4371.8 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8800
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 73
telemt_upstream_connect_attempt_total 1612
telemt_upstream_connect_success_total 1584
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 1612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 4130
telemt_me_reconnect_success_total 1343
telemt_me_reader_eof_total 1392
telemt_me_idle_close_by_peer_total 1392
telemt_me_route_drop_no_conn_total 3032
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8382
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 1415
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1328
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 8379
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 55953716 (53.36 MB)
telemt_user_octets_to_client{user="hello"} 1684863068 (1.57 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 4335.5 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13956
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 1116
telemt_upstream_connect_success_total 1116
telemt_upstream_connect_attempts_per_request{bucket="1"} 1116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 877
telemt_me_reconnect_success_total 874
telemt_me_reader_eof_total 867
telemt_me_idle_close_by_peer_total 867
telemt_me_route_drop_no_conn_total 4285
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13252
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
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 855
telemt_me_writer_restored_same_endpoint_total 854
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 13251
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 128761344 (122.80 MB)
telemt_user_octets_to_client{user="hello"} 14760133356 (13.75 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 4311.1 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15718
telemt_connections_bad_total 1020
telemt_handshake_timeouts_total 62
telemt_upstream_connect_attempt_total 1172
telemt_upstream_connect_success_total 1129
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 1172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 905
telemt_me_reconnect_success_total 882
telemt_me_reader_eof_total 894
telemt_me_idle_close_by_peer_total 894
telemt_me_route_drop_no_conn_total 4371
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13616
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 51
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 894
telemt_me_writer_restored_same_endpoint_total 874
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 13615
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 552546248 (526.95 MB)
telemt_user_octets_to_client{user="hello"} 4270267264 (3.98 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 4280.5 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8244
telemt_connections_bad_total 878
telemt_handshake_timeouts_total 92
telemt_upstream_connect_attempt_total 1504
telemt_upstream_connect_success_total 1452
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 1504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 923
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 3583
telemt_me_reconnect_success_total 1213
telemt_me_reader_eof_total 1262
telemt_me_idle_close_by_peer_total 1262
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 2168
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7093
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 132
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 96
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_me_writer_removed_unexpected_total 1285
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1200
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 7091
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 23772968 (22.67 MB)
telemt_user_octets_to_client{user="hello"} 1021144816 (973.84 MB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 4267.4 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20209
telemt_connections_bad_total 520
telemt_handshake_timeouts_total 195
telemt_upstream_connect_attempt_total 726
telemt_upstream_connect_success_total 722
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 487
telemt_me_reconnect_success_total 486
telemt_me_reader_eof_total 493
telemt_me_idle_close_by_peer_total 493
telemt_me_route_drop_no_conn_total 9353
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18739
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 492
telemt_me_writer_restored_same_endpoint_total 479
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 18711
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 1384171032 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 16028529444 (14.93 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 39
```