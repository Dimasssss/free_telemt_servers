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

# Server Metrics 2026-03-14 23:11:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 3422.1 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7009
telemt_connections_bad_total 240
telemt_handshake_timeouts_total 175
telemt_upstream_connect_attempt_total 870
telemt_upstream_connect_success_total 866
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 673
telemt_me_reconnect_success_total 669
telemt_me_reader_eof_total 668
telemt_me_idle_close_by_peer_total 668
telemt_me_route_drop_no_conn_total 1866
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6251
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
telemt_me_writer_removed_unexpected_total 659
telemt_me_writer_restored_same_endpoint_total 638
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 6251
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 62365864 (59.48 MB)
telemt_user_octets_to_client{user="hello"} 1589016772 (1.48 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 3428.8 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2384
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 1001
telemt_upstream_connect_success_total 1001
telemt_upstream_connect_attempts_per_request{bucket="1"} 1001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 570
telemt_me_reconnect_attempts_total 803
telemt_me_reconnect_success_total 802
telemt_me_reader_eof_total 819
telemt_me_idle_close_by_peer_total 819
telemt_me_route_drop_no_conn_total 940
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2255
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 799
telemt_me_writer_restored_same_endpoint_total 786
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 2255
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 19069808 (18.19 MB)
telemt_user_octets_to_client{user="hello"} 397424956 (379.01 MB)
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 3421.5 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3356
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 58
telemt_upstream_connect_attempt_total 894
telemt_upstream_connect_success_total 893
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 698
telemt_me_reconnect_success_total 690
telemt_me_reader_eof_total 720
telemt_me_idle_close_by_peer_total 720
telemt_me_route_drop_no_conn_total 1023
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3171
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 685
telemt_me_writer_restored_same_endpoint_total 686
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 3164
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 308916716 (294.61 MB)
telemt_user_octets_to_client{user="hello"} 5707093504 (5.32 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 3421.3 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3253
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 829
telemt_upstream_connect_success_total 829
telemt_upstream_connect_attempts_per_request{bucket="1"} 829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 637
telemt_me_reconnect_success_total 634
telemt_me_reader_eof_total 640
telemt_me_idle_close_by_peer_total 640
telemt_me_route_drop_no_conn_total 1477
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3143
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
telemt_me_writer_removed_unexpected_total 629
telemt_me_writer_restored_same_endpoint_total 623
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 3143
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 63380524 (60.44 MB)
telemt_user_octets_to_client{user="hello"} 4407222424 (4.10 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 3421.2 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4349
telemt_connections_bad_total 663
telemt_handshake_timeouts_total 324
telemt_upstream_connect_attempt_total 1204
telemt_upstream_connect_success_total 1188
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 1204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 541
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 1061
telemt_me_reconnect_success_total 995
telemt_me_reader_eof_total 995
telemt_me_idle_close_by_peer_total 995
telemt_me_route_drop_no_conn_total 896
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3279
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 982
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 983
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 3277
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 32019240 (30.54 MB)
telemt_user_octets_to_client{user="hello"} 3461000200 (3.22 GB)
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 3420.3 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10850
telemt_connections_bad_total 116
telemt_handshake_timeouts_total 44
telemt_upstream_connect_attempt_total 799
telemt_upstream_connect_success_total 795
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 404
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 601
telemt_me_reconnect_success_total 599
telemt_me_reader_eof_total 585
telemt_me_idle_close_by_peer_total 585
telemt_me_route_drop_no_conn_total 5224
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10324
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
telemt_me_writer_removed_unexpected_total 578
telemt_me_writer_restored_same_endpoint_total 572
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 10324
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 151374300 (144.36 MB)
telemt_user_octets_to_client{user="hello"} 9847078484 (9.17 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 37
```