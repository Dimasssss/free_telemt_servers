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

# Server Metrics 2026-03-15 09:11:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 39412.5 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150203
telemt_connections_bad_total 1142
telemt_handshake_timeouts_total 3811
telemt_upstream_connect_attempt_total 9730
telemt_upstream_connect_success_total 9675
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 9730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5376
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 8934
telemt_me_reconnect_success_total 7720
telemt_me_reader_eof_total 8253
telemt_me_idle_close_by_peer_total 8253
telemt_me_route_drop_no_conn_total 322989
telemt_me_route_drop_channel_closed_total 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190606
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1099
telemt_desync_full_logged_total 454
telemt_desync_suppressed_total 645
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 444
telemt_desync_frames_bucket_total{bucket="gt_10"} 467
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7828
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 7689
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 139763
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 1874111824 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 144162819144 (134.26 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 39419.6 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46577
telemt_connections_bad_total 300
telemt_handshake_timeouts_total 2646
telemt_upstream_connect_attempt_total 10704
telemt_upstream_connect_success_total 10704
telemt_upstream_connect_attempts_per_request{bucket="1"} 10704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6085
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11039
telemt_me_reconnect_success_total 8724
telemt_me_reader_eof_total 9386
telemt_me_idle_close_by_peer_total 9386
telemt_me_route_drop_no_conn_total 23473
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42039
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8884
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 8708
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 42040
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 908153580 (866.08 MB)
telemt_user_octets_to_client{user="hello"} 15628893144 (14.56 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 39412.2 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55645
telemt_connections_bad_total 496
telemt_handshake_timeouts_total 1935
telemt_upstream_connect_attempt_total 10425
telemt_upstream_connect_success_total 10424
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5859
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8499
telemt_me_reconnect_success_total 8456
telemt_me_reader_eof_total 9141
telemt_me_idle_close_by_peer_total 9141
telemt_me_route_drop_no_conn_total 19989
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50889
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 26
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8538
telemt_me_writer_restored_same_endpoint_total 8452
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 50818
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 9080546872 (8.46 GB)
telemt_user_octets_to_client{user="hello"} 33330822316 (31.04 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 39411.8 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69687
telemt_connections_bad_total 181
telemt_handshake_timeouts_total 432
telemt_upstream_connect_attempt_total 9393
telemt_upstream_connect_success_total 9392
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4939
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7470
telemt_me_reconnect_success_total 7439
telemt_me_reader_eof_total 7949
telemt_me_idle_close_by_peer_total 7949
telemt_me_route_drop_no_conn_total 29647
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63302
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 133
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 93
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7516
telemt_me_writer_restored_same_endpoint_total 7428
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 63234
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 1271333948 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 39124525580 (36.44 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 14483.3 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23512
telemt_connections_bad_total 2749
telemt_handshake_timeouts_total 351
telemt_upstream_connect_attempt_total 5057
telemt_upstream_connect_success_total 5011
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 5057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2773
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_reconnect_attempts_total 98497
telemt_me_reconnect_success_total 4093
telemt_me_reader_eof_total 4210
telemt_me_idle_close_by_peer_total 4210
telemt_me_route_drop_no_conn_total 7392
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19787
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 21
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 4052
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 3989
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 19927
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 176353221 (168.18 MB)
telemt_user_octets_to_client{user="hello"} 10741169195 (10.00 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 39411.1 (10h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178478
telemt_connections_bad_total 22481
telemt_handshake_timeouts_total 1049
telemt_upstream_connect_attempt_total 8459
telemt_upstream_connect_success_total 8409
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 8459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4136
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 6482
telemt_me_reconnect_success_total 6449
telemt_me_reader_eof_total 6877
telemt_me_idle_close_by_peer_total 6877
telemt_me_route_drop_no_conn_total 84882
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150159
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 6488
telemt_me_writer_restored_same_endpoint_total 6422
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 148700
telemt_user_connections_current{user="hello"} 448
telemt_user_octets_from_client{user="hello"} 4043995064 (3.77 GB)
telemt_user_octets_to_client{user="hello"} 76997446304 (71.71 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 75
```