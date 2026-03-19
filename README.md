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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-19 09:48:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 43188.6 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 918143
telemt_connections_bad_total 82444
telemt_connections_current 1728
telemt_connections_me_current 1728
telemt_handshake_timeouts_total 34667
telemt_upstream_connect_attempt_total 8184
telemt_upstream_connect_success_total 8043
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 8184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 7052
telemt_me_reconnect_success_total 5894
telemt_me_reader_eof_total 6244
telemt_me_idle_close_by_peer_total 6243
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 308207
telemt_me_route_drop_channel_closed_total 122
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 709744
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4309
telemt_desync_full_logged_total 1308
telemt_desync_suppressed_total 3001
telemt_desync_frames_bucket_total{bucket="1_2"} 1437
telemt_desync_frames_bucket_total{bucket="3_10"} 1581
telemt_desync_frames_bucket_total{bucket="gt_10"} 1291
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 6002
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5875
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 704161
telemt_user_connections_current{user="hello"} 1728
telemt_user_octets_from_client{user="hello"} 11192877296 (10.42 GB)
telemt_user_octets_to_client{user="hello"} 226024274488 (210.50 GB)
telemt_user_unique_ips_current{user="hello"} 564
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 43192.8 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2277065
telemt_connections_bad_total 143918
telemt_connections_current 4194
telemt_connections_me_current 4194
telemt_handshake_timeouts_total 50835
telemt_upstream_connect_attempt_total 8211
telemt_upstream_connect_success_total 8060
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 8211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4011
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 8240
telemt_me_reconnect_success_total 5892
telemt_me_reader_eof_total 6265
telemt_me_idle_close_by_peer_total 6265
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 992443
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1877377
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8632
telemt_desync_full_logged_total 2862
telemt_desync_suppressed_total 5770
telemt_desync_frames_bucket_total{bucket="1_2"} 1580
telemt_desync_frames_bucket_total{bucket="3_10"} 3359
telemt_desync_frames_bucket_total{bucket="gt_10"} 3693
telemt_pool_swap_total 32
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6069
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 5870
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 1877129
telemt_user_connections_current{user="hello"} 4194
telemt_user_octets_from_client{user="hello"} 30139647136 (28.07 GB)
telemt_user_octets_to_client{user="hello"} 688517955908 (641.23 GB)
telemt_user_unique_ips_current{user="hello"} 1437
telemt_user_unique_ips_recent_window{user="hello"} 688
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 43190.4 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1909682
telemt_connections_bad_total 229967
telemt_connections_current 3170
telemt_connections_me_current 3170
telemt_handshake_timeouts_total 46151
telemt_upstream_connect_attempt_total 7707
telemt_upstream_connect_success_total 7707
telemt_upstream_connect_attempts_per_request{bucket="1"} 7707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3654
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 5574
telemt_me_reconnect_success_total 5539
telemt_me_reader_eof_total 5856
telemt_me_idle_close_by_peer_total 5856
telemt_me_route_drop_no_conn_total 885852
telemt_me_route_drop_channel_closed_total 61
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1486022
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6736
telemt_desync_full_logged_total 2122
telemt_desync_suppressed_total 4614
telemt_desync_frames_bucket_total{bucket="1_2"} 1508
telemt_desync_frames_bucket_total{bucket="3_10"} 2477
telemt_desync_frames_bucket_total{bucket="gt_10"} 2751
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 5636
telemt_me_writer_restored_same_endpoint_total 5523
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 1484622
telemt_user_connections_current{user="hello"} 3170
telemt_user_octets_from_client{user="hello"} 22721785256 (21.16 GB)
telemt_user_octets_to_client{user="hello"} 681781019796 (634.96 GB)
telemt_user_unique_ips_current{user="hello"} 1066
telemt_user_unique_ips_recent_window{user="hello"} 491
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 43242.9 (12h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1971857
telemt_connections_bad_total 104877
telemt_connections_current 3155
telemt_connections_me_current 3155
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 50987
telemt_upstream_connect_attempt_total 15891
telemt_upstream_connect_success_total 15775
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 15891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4405
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 7857
telemt_me_reconnect_success_total 5442
telemt_me_reader_eof_total 5783
telemt_me_idle_close_by_peer_total 5782
telemt_me_route_drop_no_conn_total 989612
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1479851
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5388
telemt_desync_full_logged_total 1837
telemt_desync_suppressed_total 3551
telemt_desync_frames_bucket_total{bucket="1_2"} 1115
telemt_desync_frames_bucket_total{bucket="3_10"} 2105
telemt_desync_frames_bucket_total{bucket="gt_10"} 2168
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 5716
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 5418
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 274
telemt_user_connections_total{user="hello"} 1486526
telemt_user_connections_current{user="hello"} 3155
telemt_user_octets_from_client{user="hello"} 17425198064 (16.23 GB)
telemt_user_octets_to_client{user="hello"} 431808533214 (402.15 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1027
telemt_user_unique_ips_recent_window{user="hello"} 506
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 43186.3 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2294350
telemt_connections_bad_total 548909
telemt_connections_current 3558
telemt_connections_me_current 3558
telemt_handshake_timeouts_total 48363
telemt_upstream_connect_attempt_total 7457
telemt_upstream_connect_success_total 7405
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 7457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 5294
telemt_me_reconnect_success_total 5250
telemt_me_reader_eof_total 5560
telemt_me_idle_close_by_peer_total 5560
telemt_me_route_drop_no_conn_total 662201
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1472728
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6796
telemt_desync_full_logged_total 2113
telemt_desync_suppressed_total 4683
telemt_desync_frames_bucket_total{bucket="1_2"} 1356
telemt_desync_frames_bucket_total{bucket="3_10"} 2984
telemt_desync_frames_bucket_total{bucket="gt_10"} 2456
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 5327
telemt_me_writer_restored_same_endpoint_total 5226
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 1471898
telemt_user_connections_current{user="hello"} 3558
telemt_user_octets_from_client{user="hello"} 27529574024 (25.64 GB)
telemt_user_octets_to_client{user="hello"} 647015039480 (602.58 GB)
telemt_user_unique_ips_current{user="hello"} 1171
telemt_user_unique_ips_recent_window{user="hello"} 589
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 43198.2 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 409044
telemt_connections_bad_total 17945
telemt_connections_current 992
telemt_connections_me_current 992
telemt_handshake_timeouts_total 3285
telemt_upstream_connect_attempt_total 10894
telemt_upstream_connect_success_total 10622
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 10894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 13849
telemt_me_reconnect_success_total 8462
telemt_me_reader_eof_total 8983
telemt_me_idle_close_by_peer_total 8983
telemt_me_route_drop_no_conn_total 207872
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 367275
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 621
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 409
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 247
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 21
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 8700
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 8432
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 238
telemt_user_connections_total{user="hello"} 367248
telemt_user_connections_current{user="hello"} 992
telemt_user_octets_from_client{user="hello"} 5637749032 (5.25 GB)
telemt_user_octets_to_client{user="hello"} 145180185288 (135.21 GB)
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 43188.8 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1551422
telemt_connections_bad_total 132097
telemt_connections_current 3163
telemt_connections_me_current 3163
telemt_handshake_timeouts_total 66285
telemt_upstream_connect_attempt_total 8744
telemt_upstream_connect_success_total 8743
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 7926
telemt_me_reconnect_success_total 6575
telemt_me_reader_eof_total 6961
telemt_me_idle_close_by_peer_total 6960
telemt_me_route_drop_no_conn_total 604566
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1295110
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7321
telemt_desync_full_logged_total 2399
telemt_desync_suppressed_total 4922
telemt_desync_frames_bucket_total{bucket="1_2"} 1395
telemt_desync_frames_bucket_total{bucket="3_10"} 2747
telemt_desync_frames_bucket_total{bucket="gt_10"} 3179
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6695
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6560
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 1293965
telemt_user_connections_current{user="hello"} 3163
telemt_user_octets_from_client{user="hello"} 17750461148 (16.53 GB)
telemt_user_octets_to_client{user="hello"} 629014345124 (585.82 GB)
telemt_user_unique_ips_current{user="hello"} 1015
telemt_user_unique_ips_recent_window{user="hello"} 480
```