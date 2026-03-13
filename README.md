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

# Server Metrics 2026-03-13 15:20:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 114418.7 (31h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 475124
telemt_connections_bad_total 3230
telemt_handshake_timeouts_total 8656
telemt_upstream_connect_attempt_total 28680
telemt_upstream_connect_success_total 28543
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 28680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15605
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2476
telemt_me_reconnect_attempts_total 26333
telemt_me_reconnect_success_total 22800
telemt_me_reader_eof_total 24356
telemt_me_idle_close_by_peer_total 24355
telemt_me_route_drop_no_conn_total 155085
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 417049
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1360
telemt_desync_full_logged_total 480
telemt_desync_suppressed_total 880
telemt_desync_frames_bucket_total{bucket="1_2"} 300
telemt_desync_frames_bucket_total{bucket="3_10"} 487
telemt_desync_frames_bucket_total{bucket="gt_10"} 573
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 23149
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 22784
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 349
telemt_user_connections_total{user="hello"} 416626
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 7477319468 (6.96 GB)
telemt_user_octets_to_client{user="hello"} 194149254868 (180.82 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 114311.3 (31h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227102
telemt_connections_bad_total 1836
telemt_handshake_timeouts_total 1583
telemt_upstream_connect_attempt_total 84586
telemt_upstream_connect_success_total 83815
telemt_upstream_connect_fail_total 771
telemt_upstream_connect_attempts_per_request{bucket="1"} 84586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 899
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 771
telemt_me_keepalive_timeout_total 1404
telemt_me_reconnect_attempts_total 112178
telemt_me_reconnect_success_total 26022
telemt_me_reader_eof_total 29473
telemt_me_idle_close_by_peer_total 29473
telemt_me_route_drop_no_conn_total 81222
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162870
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 28938
telemt_me_refill_failed_total 2688
telemt_me_writer_restored_same_endpoint_total 26005
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2916
telemt_user_connections_total{user="hello"} 214758
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 2178725900 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 68188703782 (63.51 GB)
telemt_user_msgs_from_client{user="hello"} 782048
telemt_user_msgs_to_client{user="hello"} 5081662
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 114275.3 (31h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274508
telemt_connections_bad_total 2430
telemt_handshake_timeouts_total 12585
telemt_upstream_connect_attempt_total 30681
telemt_upstream_connect_success_total 30677
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 30681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16426
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2329
telemt_me_reconnect_attempts_total 26155
telemt_me_reconnect_success_total 24935
telemt_me_reader_eof_total 26718
telemt_me_idle_close_by_peer_total 26718
telemt_me_route_drop_no_conn_total 99066
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249704
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 25209
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 24915
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 249618
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 9572629704 (8.92 GB)
telemt_user_octets_to_client{user="hello"} 106637281624 (99.31 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 114250.6 (31h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373953
telemt_connections_bad_total 15045
telemt_handshake_timeouts_total 3710
telemt_upstream_connect_attempt_total 42689
telemt_upstream_connect_success_total 32532
telemt_upstream_connect_fail_total 10157
telemt_upstream_connect_attempts_per_request{bucket="1"} 42689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15922
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10157
telemt_me_keepalive_timeout_total 4162
telemt_me_reconnect_attempts_total 101172
telemt_me_reconnect_success_total 23789
telemt_me_reader_eof_total 26913
telemt_me_idle_close_by_peer_total 26906
telemt_me_route_drop_no_conn_total 134260
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 323908
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1271
telemt_desync_full_logged_total 379
telemt_desync_suppressed_total 892
telemt_desync_frames_bucket_total{bucket="1_2"} 314
telemt_desync_frames_bucket_total{bucket="3_10"} 474
telemt_desync_frames_bucket_total{bucket="gt_10"} 483
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 26512
telemt_me_refill_failed_total 2413
telemt_me_writer_restored_same_endpoint_total 23779
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2723
telemt_user_connections_total{user="hello"} 326818
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 6898956222 (6.43 GB)
telemt_user_octets_to_client{user="hello"} 123201971821 (114.74 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 64422.0 (17h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100088
telemt_connections_bad_total 12904
telemt_handshake_timeouts_total 1240
telemt_upstream_connect_attempt_total 26307
telemt_upstream_connect_success_total 26081
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 26307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12386
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 1043
telemt_me_reconnect_attempts_total 29120
telemt_me_reconnect_success_total 17948
telemt_me_reader_eof_total 19247
telemt_me_idle_close_by_peer_total 19247
telemt_me_route_drop_no_conn_total 30378
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77808
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 18451
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 17930
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 503
telemt_user_connections_total{user="hello"} 82707
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 952796497 (908.66 MB)
telemt_user_octets_to_client{user="hello"} 25129615055 (23.40 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 114208.3 (31h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 685396
telemt_connections_bad_total 21127
telemt_handshake_timeouts_total 21866
telemt_upstream_connect_attempt_total 23963
telemt_upstream_connect_success_total 23842
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 23963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12643
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 2551
telemt_me_reconnect_attempts_total 22807
telemt_me_reconnect_success_total 18181
telemt_me_reader_eof_total 19511
telemt_me_idle_close_by_peer_total 19508
telemt_me_route_drop_no_conn_total 326370
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 646738
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 527
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 333
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 198
telemt_desync_frames_bucket_total{bucket="gt_10"} 199
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 18559
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18174
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 378
telemt_user_connections_total{user="hello"} 619690
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 10559452540 (9.83 GB)
telemt_user_octets_to_client{user="hello"} 321974011152 (299.86 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 73
```