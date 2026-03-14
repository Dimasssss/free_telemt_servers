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

# Server Metrics 2026-03-14 23:01:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 2811.8 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5895
telemt_connections_bad_total 239
telemt_handshake_timeouts_total 103
telemt_upstream_connect_attempt_total 735
telemt_upstream_connect_success_total 731
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 538
telemt_me_reconnect_success_total 535
telemt_me_reader_eof_total 520
telemt_me_idle_close_by_peer_total 520
telemt_me_route_drop_no_conn_total 1629
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5318
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 36
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 523
telemt_me_writer_restored_same_endpoint_total 504
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 5318
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 55710660 (53.13 MB)
telemt_user_octets_to_client{user="hello"} 1438804240 (1.34 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 2818.3 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1696
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 849
telemt_upstream_connect_success_total 849
telemt_upstream_connect_attempts_per_request{bucket="1"} 849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 481
telemt_me_reconnect_attempts_total 651
telemt_me_reconnect_success_total 651
telemt_me_reader_eof_total 650
telemt_me_idle_close_by_peer_total 650
telemt_me_route_drop_no_conn_total 745
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1597
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 646
telemt_me_writer_restored_same_endpoint_total 635
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 1597
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 15361324 (14.65 MB)
telemt_user_octets_to_client{user="hello"} 359097632 (342.46 MB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 2810.8 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2699
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 770
telemt_upstream_connect_success_total 770
telemt_upstream_connect_attempts_per_request{bucket="1"} 770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 432
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 574
telemt_me_reconnect_success_total 568
telemt_me_reader_eof_total 581
telemt_me_idle_close_by_peer_total 581
telemt_me_route_drop_no_conn_total 838
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2543
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 559
telemt_me_writer_restored_same_endpoint_total 564
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 2536
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 303813076 (289.74 MB)
telemt_user_octets_to_client{user="hello"} 4958180444 (4.62 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 2810.6 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2591
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 694
telemt_upstream_connect_success_total 694
telemt_upstream_connect_attempts_per_request{bucket="1"} 694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 387
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 502
telemt_me_reconnect_success_total 500
telemt_me_reader_eof_total 499
telemt_me_idle_close_by_peer_total 499
telemt_me_route_drop_no_conn_total 1126
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2514
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 495
telemt_me_writer_restored_same_endpoint_total 489
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 2514
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 56210828 (53.61 MB)
telemt_user_octets_to_client{user="hello"} 4242505432 (3.95 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 2810.7 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3585
telemt_connections_bad_total 553
telemt_handshake_timeouts_total 180
telemt_upstream_connect_attempt_total 1026
telemt_upstream_connect_success_total 1010
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 1026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 883
telemt_me_reconnect_success_total 817
telemt_me_reader_eof_total 786
telemt_me_idle_close_by_peer_total 786
telemt_me_route_drop_no_conn_total 733
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2781
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 804
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 805
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 2779
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 28835732 (27.50 MB)
telemt_user_octets_to_client{user="hello"} 3364378648 (3.13 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 2809.9 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8616
telemt_connections_bad_total 112
telemt_handshake_timeouts_total 26
telemt_upstream_connect_attempt_total 675
telemt_upstream_connect_success_total 671
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 477
telemt_me_reconnect_success_total 476
telemt_me_reader_eof_total 453
telemt_me_idle_close_by_peer_total 453
telemt_me_route_drop_no_conn_total 4153
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8202
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 455
telemt_me_writer_restored_same_endpoint_total 449
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 8202
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 134217992 (128.00 MB)
telemt_user_octets_to_client{user="hello"} 8406342288 (7.83 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 35
```