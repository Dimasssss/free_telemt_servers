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

# Server Metrics 2026-03-15 07:19:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 32691.9 (9h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100586
telemt_connections_bad_total 696
telemt_handshake_timeouts_total 2298
telemt_upstream_connect_attempt_total 7887
telemt_upstream_connect_success_total 7840
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 7887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4265
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6221
telemt_me_reconnect_success_total 6198
telemt_me_reader_eof_total 6642
telemt_me_idle_close_by_peer_total 6642
telemt_me_route_drop_no_conn_total 129883
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110595
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 824
telemt_desync_full_logged_total 357
telemt_desync_suppressed_total 467
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 336
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6251
telemt_me_writer_restored_same_endpoint_total 6167
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 93675
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 1317652320 (1.23 GB)
telemt_user_octets_to_client{user="hello"} 67187527008 (62.57 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 32699.0 (9h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32862
telemt_connections_bad_total 221
telemt_handshake_timeouts_total 383
telemt_upstream_connect_attempt_total 8758
telemt_upstream_connect_success_total 8758
telemt_upstream_connect_attempts_per_request{bucket="1"} 8758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7135
telemt_me_reconnect_success_total 7105
telemt_me_reader_eof_total 7642
telemt_me_idle_close_by_peer_total 7642
telemt_me_route_drop_no_conn_total 16825
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30959
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 7171
telemt_me_writer_restored_same_endpoint_total 7089
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 30962
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 775283208 (739.37 MB)
telemt_user_octets_to_client{user="hello"} 11917691092 (11.10 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 32693.2 (9h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41632
telemt_connections_bad_total 458
telemt_handshake_timeouts_total 1805
telemt_upstream_connect_attempt_total 8682
telemt_upstream_connect_success_total 8681
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7061
telemt_me_reconnect_success_total 7030
telemt_me_reader_eof_total 7609
telemt_me_idle_close_by_peer_total 7609
telemt_me_route_drop_no_conn_total 14384
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37511
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 7092
telemt_me_writer_restored_same_endpoint_total 7026
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 37449
telemt_user_connections_current{user="hello"} 89
telemt_user_octets_from_client{user="hello"} 8837023044 (8.23 GB)
telemt_user_octets_to_client{user="hello"} 20214703196 (18.83 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 32691.3 (9h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48117
telemt_connections_bad_total 135
telemt_handshake_timeouts_total 347
telemt_upstream_connect_attempt_total 7652
telemt_upstream_connect_success_total 7650
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6036
telemt_me_reconnect_success_total 6011
telemt_me_reader_eof_total 6449
telemt_me_idle_close_by_peer_total 6449
telemt_me_route_drop_no_conn_total 20866
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43358
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 81
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6075
telemt_me_writer_restored_same_endpoint_total 6000
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 43278
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 790690792 (754.06 MB)
telemt_user_octets_to_client{user="hello"} 26733667420 (24.90 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 7762.8 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11201
telemt_connections_bad_total 1508
telemt_handshake_timeouts_total 156
telemt_upstream_connect_attempt_total 3107
telemt_upstream_connect_success_total 3070
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 3107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1721
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 96895
telemt_me_reconnect_success_total 2498
telemt_me_reader_eof_total 2514
telemt_me_idle_close_by_peer_total 2514
telemt_me_route_drop_no_conn_total 3130
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9183
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2441
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 2394
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 9328
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 68731057 (65.55 MB)
telemt_user_octets_to_client{user="hello"} 6845173091 (6.38 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 32690.6 (9h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134135
telemt_connections_bad_total 18912
telemt_handshake_timeouts_total 540
telemt_upstream_connect_attempt_total 7116
telemt_upstream_connect_success_total 7074
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 7116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_reconnect_attempts_total 5452
telemt_me_reconnect_success_total 5426
telemt_me_reader_eof_total 5788
telemt_me_idle_close_by_peer_total 5788
telemt_me_route_drop_no_conn_total 63226
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111295
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5454
telemt_me_writer_restored_same_endpoint_total 5399
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 109829
telemt_user_connections_current{user="hello"} 339
telemt_user_octets_from_client{user="hello"} 2795172948 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 58320312868 (54.32 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 62
```