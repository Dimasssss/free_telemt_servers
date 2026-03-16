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

# Server Metrics 2026-03-16 09:00:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 125170.6 (34h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 593065
telemt_connections_bad_total 8518
telemt_handshake_timeouts_total 20766
telemt_upstream_connect_attempt_total 29187
telemt_upstream_connect_success_total 29047
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 29187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16069
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 26290
telemt_me_reconnect_success_total 22850
telemt_me_reader_eof_total 24429
telemt_me_idle_close_by_peer_total 24429
telemt_me_route_drop_no_conn_total 532956
telemt_me_route_drop_channel_closed_total 85
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 584609
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2772
telemt_desync_full_logged_total 1086
telemt_desync_suppressed_total 1686
telemt_desync_frames_bucket_total{bucket="1_2"} 613
telemt_desync_frames_bucket_total{bucket="3_10"} 1062
telemt_desync_frames_bucket_total{bucket="gt_10"} 1097
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23209
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 22816
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 359
telemt_user_connections_total{user="hello"} 523417
telemt_user_connections_current{user="hello"} 558
telemt_user_octets_from_client{user="hello"} 10149732840 (9.45 GB)
telemt_user_octets_to_client{user="hello"} 330438951416 (307.75 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 125177.8 (34h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241817
telemt_connections_bad_total 3285
telemt_handshake_timeouts_total 15233
telemt_upstream_connect_attempt_total 33509
telemt_upstream_connect_success_total 33434
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 33509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18360
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 36102
telemt_me_reconnect_success_total 26813
telemt_me_reader_eof_total 28762
telemt_me_idle_close_by_peer_total 28761
telemt_me_route_drop_no_conn_total 116544
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214942
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 179
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 67
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 27473
telemt_me_refill_failed_total 282
telemt_me_writer_restored_same_endpoint_total 26797
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 660
telemt_user_connections_total{user="hello"} 214482
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 4797537613 (4.47 GB)
telemt_user_octets_to_client{user="hello"} 119240331144 (111.05 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 125170.1 (34h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253651
telemt_connections_bad_total 5748
telemt_handshake_timeouts_total 5100
telemt_upstream_connect_attempt_total 34801
telemt_upstream_connect_success_total 34793
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 34801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19684
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 35929
telemt_me_reconnect_success_total 28517
telemt_me_reader_eof_total 30680
telemt_me_idle_close_by_peer_total 30679
telemt_me_route_drop_no_conn_total 88227
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204616
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 100
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 29029
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 28509
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 204318
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 17624165521 (16.41 GB)
telemt_user_octets_to_client{user="hello"} 115252682624 (107.34 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 125169.3 (34h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358224
telemt_connections_bad_total 1373
telemt_handshake_timeouts_total 3092
telemt_upstream_connect_attempt_total 28890
telemt_upstream_connect_success_total 28856
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 28890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14864
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 22783
telemt_me_reconnect_success_total 22639
telemt_me_reader_eof_total 24170
telemt_me_idle_close_by_peer_total 24169
telemt_me_route_drop_no_conn_total 124817
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330855
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1204
telemt_desync_full_logged_total 414
telemt_desync_suppressed_total 790
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 517
telemt_desync_frames_bucket_total{bucket="gt_10"} 439
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 22935
telemt_me_writer_restored_same_endpoint_total 22628
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 296
telemt_user_connections_total{user="hello"} 330735
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 5220359030 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 137651317792 (128.20 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 100240.8 (27h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230505
telemt_connections_bad_total 36845
telemt_handshake_timeouts_total 4146
telemt_upstream_connect_attempt_total 28580
telemt_upstream_connect_success_total 28423
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 28580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 117765
telemt_me_reconnect_success_total 23266
telemt_me_reader_eof_total 24717
telemt_me_idle_close_by_peer_total 24717
telemt_me_route_drop_no_conn_total 71956
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182909
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 584
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 447
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 239
telemt_desync_frames_bucket_total{bucket="gt_10"} 255
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 23463
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 23162
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 182527
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 2427830389 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 77029061071 (71.74 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 125169.0 (34h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 838952
telemt_connections_bad_total 72522
telemt_handshake_timeouts_total 9717
telemt_upstream_connect_attempt_total 26152
telemt_upstream_connect_success_total 26015
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 26152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13554
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 21136
telemt_me_reconnect_success_total 19786
telemt_me_reader_eof_total 21133
telemt_me_idle_close_by_peer_total 21133
telemt_me_route_drop_no_conn_total 655757
telemt_me_route_drop_channel_closed_total 114
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 831119
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 20065
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 19759
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 689747
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 14875964356 (13.85 GB)
telemt_user_octets_to_client{user="hello"} 416961458112 (388.33 GB)
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 108
```