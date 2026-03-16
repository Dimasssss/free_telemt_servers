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

# Server Metrics 2026-03-16 19:49:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 3840.0 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30222
telemt_connections_bad_total 277
telemt_handshake_timeouts_total 2040
telemt_upstream_connect_attempt_total 732
telemt_upstream_connect_success_total 724
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 394
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 483
telemt_me_reconnect_success_total 482
telemt_me_reader_eof_total 473
telemt_me_idle_close_by_peer_total 473
telemt_me_route_drop_no_conn_total 8987
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26709
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 135
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 109
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 29
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 474
telemt_me_writer_restored_same_endpoint_total 461
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_user_connections_total{user="hello"} 26700
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 472215880 (450.34 MB)
telemt_user_octets_to_client{user="hello"} 19374615872 (18.04 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 4091.7 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24504
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 1022
telemt_upstream_connect_attempt_total 815
telemt_upstream_connect_success_total 802
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 405
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 563
telemt_me_reconnect_success_total 563
telemt_me_reader_eof_total 564
telemt_me_idle_close_by_peer_total 564
telemt_me_route_drop_no_conn_total 10526
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22275
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 571
telemt_me_writer_restored_same_endpoint_total 547
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 22274
telemt_user_connections_current{user="hello"} 369
telemt_user_octets_from_client{user="hello"} 267498976 (255.11 MB)
telemt_user_octets_to_client{user="hello"} 7913345620 (7.37 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 3867.5 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12739
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 109
telemt_upstream_connect_attempt_total 845
telemt_upstream_connect_success_total 835
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 457
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 603
telemt_me_reconnect_success_total 589
telemt_me_reader_eof_total 594
telemt_me_idle_close_by_peer_total 594
telemt_me_route_drop_no_conn_total 4010
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12279
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 592
telemt_me_writer_restored_same_endpoint_total 578
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 12276
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 383821696 (366.04 MB)
telemt_user_octets_to_client{user="hello"} 5561227144 (5.18 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 3927.0 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25456
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 305
telemt_upstream_connect_attempt_total 805
telemt_upstream_connect_success_total 792
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 551
telemt_me_reconnect_success_total 546
telemt_me_reader_eof_total 545
telemt_me_idle_close_by_peer_total 545
telemt_me_route_drop_no_conn_total 8029
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24196
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 61
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 548
telemt_me_writer_restored_same_endpoint_total 539
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 24191
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 325986740 (310.89 MB)
telemt_user_octets_to_client{user="hello"} 8780213156 (8.18 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 3898.9 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15822
telemt_connections_bad_total 4448
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 1160
telemt_upstream_connect_success_total 1141
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 1991
telemt_me_reconnect_success_total 901
telemt_me_reader_eof_total 905
telemt_me_idle_close_by_peer_total 905
telemt_me_route_drop_no_conn_total 4105
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10856
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
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
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 926
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 893
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 10854
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 76941824 (73.38 MB)
telemt_user_octets_to_client{user="hello"} 3585779848 (3.34 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 4059.9 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39619
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 603
telemt_upstream_connect_attempt_total 776
telemt_upstream_connect_success_total 770
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 531
telemt_me_reconnect_success_total 530
telemt_me_reader_eof_total 536
telemt_me_idle_close_by_peer_total 536
telemt_me_route_drop_no_conn_total 15065
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37302
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 537
telemt_me_writer_restored_same_endpoint_total 520
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 37297
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 468681796 (446.97 MB)
telemt_user_octets_to_client{user="hello"} 21694730712 (20.20 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 60
```