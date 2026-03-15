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

# Server Metrics 2026-03-15 08:25:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 36666.8 (10h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132465
telemt_connections_bad_total 1062
telemt_handshake_timeouts_total 3431
telemt_upstream_connect_attempt_total 8779
telemt_upstream_connect_success_total 8726
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 8779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6935
telemt_me_reconnect_success_total 6909
telemt_me_reader_eof_total 7396
telemt_me_idle_close_by_peer_total 7396
telemt_me_route_drop_no_conn_total 260297
telemt_me_route_drop_channel_closed_total 38
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 160464
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 984
telemt_desync_full_logged_total 416
telemt_desync_suppressed_total 568
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 400
telemt_desync_frames_bucket_total{bucket="gt_10"} 416
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6971
telemt_me_writer_restored_same_endpoint_total 6878
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 123065
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 1684775264 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 114278594356 (106.43 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 36674.2 (10h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40024
telemt_connections_bad_total 257
telemt_handshake_timeouts_total 1711
telemt_upstream_connect_attempt_total 9938
telemt_upstream_connect_success_total 9938
telemt_upstream_connect_attempts_per_request{bucket="1"} 9938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5626
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 8137
telemt_me_reconnect_success_total 8103
telemt_me_reader_eof_total 8673
telemt_me_idle_close_by_peer_total 8673
telemt_me_route_drop_no_conn_total 20703
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36648
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 8183
telemt_me_writer_restored_same_endpoint_total 8087
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 36651
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 851618992 (812.17 MB)
telemt_user_octets_to_client{user="hello"} 13645357852 (12.71 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 36666.8 (10h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50187
telemt_connections_bad_total 479
telemt_handshake_timeouts_total 1906
telemt_upstream_connect_attempt_total 9763
telemt_upstream_connect_success_total 9762
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5466
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7967
telemt_me_reconnect_success_total 7930
telemt_me_reader_eof_total 8570
telemt_me_idle_close_by_peer_total 8570
telemt_me_route_drop_no_conn_total 17231
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45624
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8004
telemt_me_writer_restored_same_endpoint_total 7926
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 45558
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 8943473240 (8.33 GB)
telemt_user_octets_to_client{user="hello"} 28284081236 (26.34 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 36666.3 (10h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60243
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 396
telemt_upstream_connect_attempt_total 8732
telemt_upstream_connect_success_total 8731
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6940
telemt_me_reconnect_success_total 6912
telemt_me_reader_eof_total 7389
telemt_me_idle_close_by_peer_total 7389
telemt_me_route_drop_no_conn_total 26125
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54514
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 105
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6983
telemt_me_writer_restored_same_endpoint_total 6901
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 54447
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 1098904076 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 34117432276 (31.77 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 11738.0 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18479
telemt_connections_bad_total 2247
telemt_handshake_timeouts_total 180
telemt_upstream_connect_attempt_total 4134
telemt_upstream_connect_success_total 4095
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 4134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2288
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 97744
telemt_me_reconnect_success_total 3344
telemt_me_reader_eof_total 3434
telemt_me_idle_close_by_peer_total 3434
telemt_me_route_drop_no_conn_total 5454
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15519
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3297
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 3240
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 15659
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 124228809 (118.47 MB)
telemt_user_octets_to_client{user="hello"} 9819078231 (9.14 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 36665.8 (10h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158878
telemt_connections_bad_total 20916
telemt_handshake_timeouts_total 823
telemt_upstream_connect_attempt_total 7958
telemt_upstream_connect_success_total 7910
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 7958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_reconnect_attempts_total 6112
telemt_me_reconnect_success_total 6082
telemt_me_reader_eof_total 6484
telemt_me_idle_close_by_peer_total 6484
telemt_me_route_drop_no_conn_total 75776
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132876
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6117
telemt_me_writer_restored_same_endpoint_total 6055
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 131414
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 3571285240 (3.33 GB)
telemt_user_octets_to_client{user="hello"} 70662726936 (65.81 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 70
```