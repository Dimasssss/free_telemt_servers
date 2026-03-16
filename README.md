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

# Server Metrics 2026-03-16 14:27:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 2992.8 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37229
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 1027
telemt_upstream_connect_attempt_total 592
telemt_upstream_connect_success_total 590
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 390
telemt_me_reconnect_success_total 386
telemt_me_reader_eof_total 368
telemt_me_idle_close_by_peer_total 368
telemt_me_route_drop_no_conn_total 10451
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34605
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 41
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 377
telemt_me_writer_restored_same_endpoint_total 384
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 34553
telemt_user_connections_current{user="hello"} 682
telemt_user_octets_from_client{user="hello"} 836820192 (798.05 MB)
telemt_user_octets_to_client{user="hello"} 21939501288 (20.43 GB)
telemt_user_unique_ips_current{user="hello"} 205
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 557.2 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6036
telemt_connections_bad_total 188
telemt_handshake_timeouts_total 51
telemt_upstream_connect_attempt_total 5619
telemt_upstream_connect_success_total 5613
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 5619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 267
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 627
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5611
telemt_user_connections_current{user="hello"} 609
telemt_user_octets_from_client{user="hello"} 90476883 (86.29 MB)
telemt_user_octets_to_client{user="hello"} 929409412 (886.35 MB)
telemt_user_msgs_from_client{user="hello"} 94044
telemt_user_msgs_to_client{user="hello"} 282493
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 3106.9 (0h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15063
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 109
telemt_upstream_connect_attempt_total 2185
telemt_upstream_connect_success_total 2153
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 2185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 841
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 30634
telemt_me_reconnect_success_total 980
telemt_me_reader_eof_total 986
telemt_me_idle_close_by_peer_total 986
telemt_me_route_drop_no_conn_total 3616
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13174
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 1009
telemt_me_refill_failed_total 926
telemt_me_writer_restored_same_endpoint_total 936
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 14130
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 172996302 (164.98 MB)
telemt_user_octets_to_client{user="hello"} 2343709726 (2.18 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 3241.9 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26790
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 500
telemt_upstream_connect_attempt_total 780
telemt_upstream_connect_success_total 777
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 347
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1527
telemt_me_reconnect_success_total 553
telemt_me_reader_eof_total 562
telemt_me_idle_close_by_peer_total 562
telemt_me_route_drop_no_conn_total 8065
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25114
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 168
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_me_writer_removed_unexpected_total 581
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 549
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 25096
telemt_user_connections_current{user="hello"} 496
telemt_user_octets_from_client{user="hello"} 634622048 (605.22 MB)
telemt_user_octets_to_client{user="hello"} 5453207468 (5.08 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 702.4 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3455
telemt_connections_bad_total 839
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 169
telemt_upstream_connect_success_total 167
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 102
telemt_me_reconnect_success_total 101
telemt_me_reader_eof_total 70
telemt_me_idle_close_by_peer_total 70
telemt_me_route_drop_no_conn_total 673
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2459
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_me_writer_removed_unexpected_total 87
telemt_me_writer_restored_same_endpoint_total 101
telemt_me_async_recovery_trigger_total 22
telemt_user_connections_total{user="hello"} 2445
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 196720348 (187.61 MB)
telemt_user_octets_to_client{user="hello"} 390552536 (372.46 MB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 2809.6 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35505
telemt_connections_bad_total 829
telemt_handshake_timeouts_total 293
telemt_upstream_connect_attempt_total 610
telemt_upstream_connect_success_total 610
telemt_upstream_connect_attempts_per_request{bucket="1"} 610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 272
telemt_me_reconnect_attempts_total 419
telemt_me_reconnect_success_total 417
telemt_me_reader_eof_total 389
telemt_me_idle_close_by_peer_total 389
telemt_me_route_drop_no_conn_total 14463
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33459
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_me_writer_removed_unexpected_total 411
telemt_me_writer_restored_same_endpoint_total 413
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_user_connections_total{user="hello"} 33333
telemt_user_connections_current{user="hello"} 763
telemt_user_octets_from_client{user="hello"} 928599644 (885.58 MB)
telemt_user_octets_to_client{user="hello"} 9165241044 (8.54 GB)
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 92
```