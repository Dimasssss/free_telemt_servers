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

# Server Metrics 2026-03-15 07:29:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 33304.0 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104190
telemt_connections_bad_total 730
telemt_handshake_timeouts_total 2371
telemt_upstream_connect_attempt_total 7984
telemt_upstream_connect_success_total 7937
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 7984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6318
telemt_me_reconnect_success_total 6295
telemt_me_reader_eof_total 6739
telemt_me_idle_close_by_peer_total 6739
telemt_me_route_drop_no_conn_total 138048
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115462
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 854
telemt_desync_full_logged_total 368
telemt_desync_suppressed_total 486
telemt_desync_frames_bucket_total{bucket="1_2"} 147
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 352
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6348
telemt_me_writer_restored_same_endpoint_total 6264
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 97048
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 1347526604 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 71426130512 (66.52 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 33311.3 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33948
telemt_connections_bad_total 243
telemt_handshake_timeouts_total 581
telemt_upstream_connect_attempt_total 8855
telemt_upstream_connect_success_total 8855
telemt_upstream_connect_attempts_per_request{bucket="1"} 8855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7232
telemt_me_reconnect_success_total 7201
telemt_me_reader_eof_total 7740
telemt_me_idle_close_by_peer_total 7740
telemt_me_route_drop_no_conn_total 17475
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31810
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 7269
telemt_me_writer_restored_same_endpoint_total 7185
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 31813
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 786749292 (750.30 MB)
telemt_user_octets_to_client{user="hello"} 12203975804 (11.37 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 33303.8 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42939
telemt_connections_bad_total 466
telemt_handshake_timeouts_total 1817
telemt_upstream_connect_attempt_total 8801
telemt_upstream_connect_success_total 8800
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4930
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7180
telemt_me_reconnect_success_total 7148
telemt_me_reader_eof_total 7729
telemt_me_idle_close_by_peer_total 7729
telemt_me_route_drop_no_conn_total 14839
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38706
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 7212
telemt_me_writer_restored_same_endpoint_total 7144
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 38644
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 8845495148 (8.24 GB)
telemt_user_octets_to_client{user="hello"} 20495442808 (19.09 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 33303.6 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49970
telemt_connections_bad_total 136
telemt_handshake_timeouts_total 350
telemt_upstream_connect_attempt_total 7735
telemt_upstream_connect_success_total 7734
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6119
telemt_me_reconnect_success_total 6095
telemt_me_reader_eof_total 6534
telemt_me_idle_close_by_peer_total 6534
telemt_me_route_drop_no_conn_total 21669
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45025
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 87
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6160
telemt_me_writer_restored_same_endpoint_total 6084
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 44947
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 823589704 (785.44 MB)
telemt_user_octets_to_client{user="hello"} 27461525524 (25.58 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 8375.1 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12069
telemt_connections_bad_total 1633
telemt_handshake_timeouts_total 163
telemt_upstream_connect_attempt_total 3380
telemt_upstream_connect_success_total 3342
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 3380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1459
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 97124
telemt_me_reconnect_success_total 2727
telemt_me_reader_eof_total 2776
telemt_me_idle_close_by_peer_total 2776
telemt_me_route_drop_no_conn_total 3414
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9874
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2671
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 2623
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 10020
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 75957285 (72.44 MB)
telemt_user_octets_to_client{user="hello"} 8404931407 (7.83 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 33302.8 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138690
telemt_connections_bad_total 19654
telemt_handshake_timeouts_total 585
telemt_upstream_connect_attempt_total 7188
telemt_upstream_connect_success_total 7146
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 7188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_reconnect_attempts_total 5524
telemt_me_reconnect_success_total 5497
telemt_me_reader_eof_total 5859
telemt_me_idle_close_by_peer_total 5859
telemt_me_route_drop_no_conn_total 65000
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114855
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 28
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5525
telemt_me_writer_restored_same_endpoint_total 5470
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 113389
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 2833942032 (2.64 GB)
telemt_user_octets_to_client{user="hello"} 59316844720 (55.24 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 67
```