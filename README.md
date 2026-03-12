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

# Server Metrics 2026-03-12 08:32:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 3559.5 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20181
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 1929
telemt_upstream_connect_attempt_total 724
telemt_upstream_connect_success_total 722
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 528
telemt_me_reconnect_success_total 525
telemt_me_reader_eof_total 514
telemt_me_idle_close_by_peer_total 514
telemt_me_route_drop_no_conn_total 4884
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17070
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 519
telemt_me_writer_restored_same_endpoint_total 509
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_user_connections_total{user="hello"} 17069
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 159410480 (152.03 MB)
telemt_user_octets_to_client{user="hello"} 6208669812 (5.78 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 3452.5 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7190
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 1303
telemt_upstream_connect_success_total 1277
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 1303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 891
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 2587
telemt_me_reconnect_success_total 1081
telemt_me_reader_eof_total 1089
telemt_me_idle_close_by_peer_total 1089
telemt_me_route_drop_no_conn_total 2298
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6838
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 1112
telemt_me_refill_failed_total 47
telemt_me_writer_restored_same_endpoint_total 1066
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 6835
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 39210072 (37.39 MB)
telemt_user_octets_to_client{user="hello"} 1497099356 (1.39 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 3416.2 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11196
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 92
telemt_upstream_connect_attempt_total 775
telemt_upstream_connect_success_total 775
telemt_upstream_connect_attempts_per_request{bucket="1"} 775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 386
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 582
telemt_me_reconnect_success_total 580
telemt_me_reader_eof_total 571
telemt_me_idle_close_by_peer_total 571
telemt_me_route_drop_no_conn_total 3344
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10641
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
telemt_me_writer_removed_unexpected_total 559
telemt_me_writer_restored_same_endpoint_total 560
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 10641
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 107817896 (102.82 MB)
telemt_user_octets_to_client{user="hello"} 13684592764 (12.74 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 3391.8 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12458
telemt_connections_bad_total 1013
telemt_handshake_timeouts_total 45
telemt_upstream_connect_attempt_total 859
telemt_upstream_connect_success_total 821
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 468
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 641
telemt_me_reconnect_success_total 619
telemt_me_reader_eof_total 631
telemt_me_idle_close_by_peer_total 631
telemt_me_route_drop_no_conn_total 3208
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10565
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 21
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 630
telemt_me_writer_restored_same_endpoint_total 611
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 10565
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 113935932 (108.66 MB)
telemt_user_octets_to_client{user="hello"} 3029597084 (2.82 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3361.2 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6474
telemt_connections_bad_total 684
telemt_handshake_timeouts_total 89
telemt_upstream_connect_attempt_total 1168
telemt_upstream_connect_success_total 1122
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 1168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 2049
telemt_me_reconnect_success_total 927
telemt_me_reader_eof_total 937
telemt_me_idle_close_by_peer_total 937
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 1728
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5548
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 20
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 102
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_me_writer_removed_unexpected_total 959
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 914
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 5547
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 16523344 (15.76 MB)
telemt_user_octets_to_client{user="hello"} 712636224 (679.62 MB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 3348.1 (0h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16101
telemt_connections_bad_total 513
telemt_handshake_timeouts_total 172
telemt_upstream_connect_attempt_total 560
telemt_upstream_connect_success_total 556
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 272
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 364
telemt_me_reconnect_success_total 363
telemt_me_reader_eof_total 361
telemt_me_idle_close_by_peer_total 361
telemt_me_route_drop_no_conn_total 7378
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14765
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 367
telemt_me_writer_restored_same_endpoint_total 356
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 14740
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 1212959088 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 12497630484 (11.64 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 49
```