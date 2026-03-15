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

# Server Metrics 2026-03-15 12:35:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 51660.3 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226263
telemt_connections_bad_total 1808
telemt_handshake_timeouts_total 4716
telemt_upstream_connect_attempt_total 13130
telemt_upstream_connect_success_total 13060
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7242
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 13835
telemt_me_reconnect_success_total 10463
telemt_me_reader_eof_total 11184
telemt_me_idle_close_by_peer_total 11184
telemt_me_route_drop_no_conn_total 426509
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 272143
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1564
telemt_desync_full_logged_total 621
telemt_desync_suppressed_total 943
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 628
telemt_desync_frames_bucket_total{bucket="gt_10"} 676
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 10675
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 10432
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 211254
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 4178422436 (3.89 GB)
telemt_user_octets_to_client{user="hello"} 195466219288 (182.04 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 51666.9 (14h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80639
telemt_connections_bad_total 2693
telemt_handshake_timeouts_total 6417
telemt_upstream_connect_attempt_total 14173
telemt_upstream_connect_success_total 14173
telemt_upstream_connect_attempts_per_request{bucket="1"} 14173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 13886
telemt_me_reconnect_success_total 11548
telemt_me_reader_eof_total 12355
telemt_me_idle_close_by_peer_total 12355
telemt_me_route_drop_no_conn_total 35758
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68996
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 11745
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 11532
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 68994
telemt_user_connections_current{user="hello"} 264
telemt_user_octets_from_client{user="hello"} 1414325192 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 32421436372 (30.19 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 51659.4 (14h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83811
telemt_connections_bad_total 1034
telemt_handshake_timeouts_total 2633
telemt_upstream_connect_attempt_total 15118
telemt_upstream_connect_success_total 15110
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 15118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 14630
telemt_me_reconnect_success_total 12485
telemt_me_reader_eof_total 13368
telemt_me_idle_close_by_peer_total 13368
telemt_me_route_drop_no_conn_total 32404
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76479
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 12670
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 12477
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 76393
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 9565086744 (8.91 GB)
telemt_user_octets_to_client{user="hello"} 45376677460 (42.26 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 51659.0 (14h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114544
telemt_connections_bad_total 393
telemt_handshake_timeouts_total 721
telemt_upstream_connect_attempt_total 12156
telemt_upstream_connect_success_total 12155
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9615
telemt_me_reconnect_success_total 9561
telemt_me_reader_eof_total 10205
telemt_me_idle_close_by_peer_total 10205
telemt_me_route_drop_no_conn_total 45575
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104559
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 288
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 201
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9669
telemt_me_writer_restored_same_endpoint_total 9550
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 104479
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 1851810212 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 56673006236 (52.78 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 26730.3 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61593
telemt_connections_bad_total 15930
telemt_handshake_timeouts_total 875
telemt_upstream_connect_attempt_total 8584
telemt_upstream_connect_success_total 8524
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 8584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4659
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 101427
telemt_me_reconnect_success_total 7007
telemt_me_reader_eof_total 7308
telemt_me_idle_close_by_peer_total 7308
telemt_me_route_drop_no_conn_total 21461
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43392
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 110
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 7000
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 6903
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 43528
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 664731065 (633.94 MB)
telemt_user_octets_to_client{user="hello"} 17166650143 (15.99 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 51658.3 (14h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297965
telemt_connections_bad_total 47716
telemt_handshake_timeouts_total 2176
telemt_upstream_connect_attempt_total 10975
telemt_upstream_connect_success_total 10908
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 10975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_reconnect_attempts_total 8359
telemt_me_reconnect_success_total 8303
telemt_me_reader_eof_total 8841
telemt_me_idle_close_by_peer_total 8841
telemt_me_route_drop_no_conn_total 132877
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239303
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 158
telemt_desync_full_logged_total 64
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8375
telemt_me_writer_restored_same_endpoint_total 8276
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 237665
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 5009393324 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 115540349904 (107.61 GB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 79
```