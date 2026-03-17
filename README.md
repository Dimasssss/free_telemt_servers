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

# Server Metrics 2026-03-17 07:45:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 46836.3 (13h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312890
telemt_connections_bad_total 3540
telemt_handshake_timeouts_total 9793
telemt_upstream_connect_attempt_total 9593
telemt_upstream_connect_success_total 9542
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 9593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7252
telemt_me_reconnect_success_total 7223
telemt_me_reader_eof_total 7690
telemt_me_idle_close_by_peer_total 7690
telemt_me_route_drop_no_conn_total 95763
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281567
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2156
telemt_desync_full_logged_total 626
telemt_desync_suppressed_total 1530
telemt_desync_frames_bucket_total{bucket="1_2"} 471
telemt_desync_frames_bucket_total{bucket="3_10"} 1071
telemt_desync_frames_bucket_total{bucket="gt_10"} 614
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7298
telemt_me_writer_restored_same_endpoint_total 7202
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 281335
telemt_user_connections_current{user="hello"} 850
telemt_user_octets_from_client{user="hello"} 3811370004 (3.55 GB)
telemt_user_octets_to_client{user="hello"} 121787016836 (113.42 GB)
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 47088.0 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176285
telemt_connections_bad_total 2350
telemt_handshake_timeouts_total 11897
telemt_upstream_connect_attempt_total 12914
telemt_upstream_connect_success_total 12746
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 12914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_reconnect_attempts_total 12673
telemt_me_reconnect_success_total 10402
telemt_me_reader_eof_total 11010
telemt_me_idle_close_by_peer_total 11010
telemt_me_route_drop_no_conn_total 63433
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152820
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 391
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 250
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 10571
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 10386
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 152848
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 1859741300 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 62048139676 (57.79 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 46864.4 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107114
telemt_connections_bad_total 4620
telemt_handshake_timeouts_total 4857
telemt_upstream_connect_attempt_total 12258
telemt_upstream_connect_success_total 12194
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 12258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5376
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6756
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9895
telemt_me_reconnect_success_total 9837
telemt_me_reader_eof_total 10530
telemt_me_idle_close_by_peer_total 10530
telemt_me_route_drop_no_conn_total 33810
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88920
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 158
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9959
telemt_me_writer_restored_same_endpoint_total 9826
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 88876
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 6451100224 (6.01 GB)
telemt_user_octets_to_client{user="hello"} 27400593280 (25.52 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 46923.2 (13h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207321
telemt_connections_bad_total 6056
telemt_handshake_timeouts_total 10049
telemt_upstream_connect_attempt_total 10787
telemt_upstream_connect_success_total 10695
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 10787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5573
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 8347
telemt_me_reconnect_success_total 8277
telemt_me_reader_eof_total 8779
telemt_me_idle_close_by_peer_total 8779
telemt_me_route_drop_no_conn_total 62108
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175286
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 365
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 239
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 147
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8399
telemt_me_writer_restored_same_endpoint_total 8269
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 175292
telemt_user_connections_current{user="hello"} 476
telemt_user_octets_from_client{user="hello"} 1853351454 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 78714438801 (73.31 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 46895.2 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135203
telemt_connections_bad_total 38766
telemt_handshake_timeouts_total 2460
telemt_upstream_connect_attempt_total 14277
telemt_upstream_connect_success_total 14088
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 14277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_reconnect_attempts_total 14889
telemt_me_reconnect_success_total 11627
telemt_me_reader_eof_total 12271
telemt_me_idle_close_by_peer_total 12271
telemt_me_route_drop_no_conn_total 35264
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89961
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 123
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 11873
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 11619
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 90001
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 938058075 (894.60 MB)
telemt_user_octets_to_client{user="hello"} 42602563422 (39.68 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 47056.8 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 319865
telemt_connections_bad_total 42169
telemt_handshake_timeouts_total 2842
telemt_upstream_connect_attempt_total 9777
telemt_upstream_connect_success_total 9726
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 9777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5007
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 9963
telemt_me_reconnect_success_total 7368
telemt_me_reader_eof_total 7933
telemt_me_idle_close_by_peer_total 7933
telemt_me_route_drop_no_conn_total 240367
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 340411
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 358
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 198
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7554
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 7354
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 262338
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 3713030096 (3.46 GB)
telemt_user_octets_to_client{user="hello"} 164835854448 (153.52 GB)
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 35062.6 (9h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1700
telemt_connections_bad_total 195
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 17426
telemt_upstream_connect_success_total 17425
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7540
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 15709
telemt_me_reconnect_success_total 15620
telemt_me_reader_eof_total 17080
telemt_me_idle_close_by_peer_total 17080
telemt_me_route_drop_no_conn_total 259
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1488
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 15758
telemt_me_writer_restored_same_endpoint_total 15620
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 1488
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 221427808 (211.17 MB)
telemt_user_octets_to_client{user="hello"} 16624505400 (15.48 GB)
telemt_user_unique_ips_current{user="hello"} 9
```