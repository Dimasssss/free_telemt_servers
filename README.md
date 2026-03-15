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

# Server Metrics 2026-03-15 19:54:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 78001.8 (21h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366319
telemt_connections_bad_total 4450
telemt_handshake_timeouts_total 13597
telemt_upstream_connect_attempt_total 18705
telemt_upstream_connect_success_total 18612
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 18705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10317
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 18128
telemt_me_reconnect_success_total 14727
telemt_me_reader_eof_total 15700
telemt_me_idle_close_by_peer_total 15700
telemt_me_route_drop_no_conn_total 475533
telemt_me_route_drop_channel_closed_total 77
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 395407
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1945
telemt_desync_full_logged_total 765
telemt_desync_suppressed_total 1180
telemt_desync_frames_bucket_total{bucket="1_2"} 368
telemt_desync_frames_bucket_total{bucket="3_10"} 757
telemt_desync_frames_bucket_total{bucket="gt_10"} 820
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 14995
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 14693
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 334471
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 7543811792 (7.03 GB)
telemt_user_octets_to_client{user="hello"} 258014058320 (240.29 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 78007.9 (21h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150179
telemt_connections_bad_total 2857
telemt_handshake_timeouts_total 13006
telemt_upstream_connect_attempt_total 21324
telemt_upstream_connect_success_total 21284
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 21324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11558
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 514
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 1020
telemt_me_reconnect_attempts_total 19465
telemt_me_reconnect_success_total 17026
telemt_me_reader_eof_total 18162
telemt_me_idle_close_by_peer_total 18161
telemt_me_route_drop_no_conn_total 62889
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128070
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 17356
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 17010
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 330
telemt_user_connections_total{user="hello"} 128342
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 2378220897 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 62943730160 (58.62 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 78000.8 (21h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151172
telemt_connections_bad_total 1724
telemt_handshake_timeouts_total 3374
telemt_upstream_connect_attempt_total 22457
telemt_upstream_connect_success_total 22449
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 22457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 25872
telemt_me_reconnect_success_total 18507
telemt_me_reader_eof_total 19873
telemt_me_idle_close_by_peer_total 19873
telemt_me_route_drop_no_conn_total 59510
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133810
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 18922
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 18499
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 415
telemt_user_connections_total{user="hello"} 133697
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 10852958884 (10.11 GB)
telemt_user_octets_to_client{user="hello"} 74078895064 (68.99 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 78000.3 (21h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216222
telemt_connections_bad_total 1169
telemt_handshake_timeouts_total 1569
telemt_upstream_connect_attempt_total 18288
telemt_upstream_connect_success_total 18273
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 18288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9427
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 14479
telemt_me_reconnect_success_total 14391
telemt_me_reader_eof_total 15328
telemt_me_idle_close_by_peer_total 15328
telemt_me_route_drop_no_conn_total 79866
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199109
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 712
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 449
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 326
telemt_desync_frames_bucket_total{bucket="gt_10"} 242
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 14563
telemt_me_writer_restored_same_endpoint_total 14380
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 199027
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 3720336348 (3.46 GB)
telemt_user_octets_to_client{user="hello"} 90894848408 (84.65 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 53071.9 (14h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129537
telemt_connections_bad_total 25615
telemt_handshake_timeouts_total 2504
telemt_upstream_connect_attempt_total 15567
telemt_upstream_connect_success_total 15473
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 15567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7046
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8334
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 107109
telemt_me_reconnect_success_total 12659
telemt_me_reader_eof_total 13308
telemt_me_idle_close_by_peer_total 13308
telemt_me_route_drop_no_conn_total 44184
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97842
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 309
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 242
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 12743
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 12555
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 97972
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 1579281553 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 37923953867 (35.32 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 78000.2 (21h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 528702
telemt_connections_bad_total 58018
telemt_handshake_timeouts_total 4276
telemt_upstream_connect_attempt_total 16614
telemt_upstream_connect_success_total 16519
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 16614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8560
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 13917
telemt_me_reconnect_success_total 12607
telemt_me_reader_eof_total 13397
telemt_me_idle_close_by_peer_total 13397
telemt_me_route_drop_no_conn_total 366789
telemt_me_route_drop_channel_closed_total 91
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 506656
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 322
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 12783
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 12580
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 446769
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 11378989068 (10.60 GB)
telemt_user_octets_to_client{user="hello"} 253256253676 (235.86 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 56
```