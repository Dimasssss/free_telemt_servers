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

# Server Metrics 2026-03-16 13:26:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 141113.0 (39h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 803756
telemt_connections_bad_total 54286
telemt_handshake_timeouts_total 26879
telemt_upstream_connect_attempt_total 32595
telemt_upstream_connect_success_total 32437
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 32595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17895
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 39662
telemt_me_reconnect_success_total 25426
telemt_me_reader_eof_total 27412
telemt_me_idle_close_by_peer_total 27412
telemt_me_route_drop_no_conn_total 621106
telemt_me_route_drop_channel_closed_total 99
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 735907
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3503
telemt_desync_full_logged_total 1315
telemt_desync_suppressed_total 2188
telemt_desync_frames_bucket_total{bucket="1_2"} 748
telemt_desync_frames_bucket_total{bucket="3_10"} 1458
telemt_desync_frames_bucket_total{bucket="gt_10"} 1297
telemt_pool_swap_total 126
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26152
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 25391
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 726
telemt_user_connections_total{user="hello"} 672376
telemt_user_connections_current{user="hello"} 743
telemt_user_octets_from_client{user="hello"} 13897738072 (12.94 GB)
telemt_user_octets_to_client{user="hello"} 382081837544 (355.84 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 141120.3 (39h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 377421
telemt_connections_bad_total 41177
telemt_handshake_timeouts_total 21950
telemt_upstream_connect_attempt_total 37586
telemt_upstream_connect_success_total 37479
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 37586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20402
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 901
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1697
telemt_me_reconnect_attempts_total 46095
telemt_me_reconnect_success_total 29835
telemt_me_reader_eof_total 32086
telemt_me_idle_close_by_peer_total 32085
telemt_me_route_drop_no_conn_total 159464
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 301876
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 258
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 173
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 30771
telemt_me_refill_failed_total 498
telemt_me_writer_restored_same_endpoint_total 29819
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 936
telemt_user_connections_total{user="hello"} 301538
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 5881736757 (5.48 GB)
telemt_user_octets_to_client{user="hello"} 144025908672 (134.13 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 141113.0 (39h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 323346
telemt_connections_bad_total 8728
telemt_handshake_timeouts_total 9081
telemt_upstream_connect_attempt_total 38883
telemt_upstream_connect_success_total 38873
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 38883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16812
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21999
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 39232
telemt_me_reconnect_success_total 31777
telemt_me_reader_eof_total 34100
telemt_me_idle_close_by_peer_total 34099
telemt_me_route_drop_no_conn_total 109218
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 263763
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 32335
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 31769
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 558
telemt_user_connections_total{user="hello"} 263352
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 19234162061 (17.91 GB)
telemt_user_octets_to_client{user="hello"} 133703387172 (124.52 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 141112.6 (39h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 499530
telemt_connections_bad_total 5609
telemt_handshake_timeouts_total 6691
telemt_upstream_connect_attempt_total 32741
telemt_upstream_connect_success_total 32691
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 32741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16753
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 128
telemt_me_reconnect_attempts_total 33100
telemt_me_reconnect_success_total 25654
telemt_me_reader_eof_total 27503
telemt_me_idle_close_by_peer_total 27502
telemt_me_route_drop_no_conn_total 165966
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 455847
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1635
telemt_desync_full_logged_total 542
telemt_desync_suppressed_total 1093
telemt_desync_frames_bucket_total{bucket="1_2"} 330
telemt_desync_frames_bucket_total{bucket="3_10"} 704
telemt_desync_frames_bucket_total{bucket="gt_10"} 601
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 26232
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 25643
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 578
telemt_user_connections_total{user="hello"} 455646
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 6911269426 (6.44 GB)
telemt_user_octets_to_client{user="hello"} 169369690028 (157.74 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 116183.9 (32h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307724
telemt_connections_bad_total 57341
telemt_handshake_timeouts_total 6305
telemt_upstream_connect_attempt_total 33077
telemt_upstream_connect_success_total 32897
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 33077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 122549
telemt_me_reconnect_success_total 26927
telemt_me_reader_eof_total 28572
telemt_me_idle_close_by_peer_total 28572
telemt_me_route_drop_no_conn_total 90822
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234766
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 722
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 546
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 293
telemt_desync_frames_bucket_total{bucket="gt_10"} 321
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 27206
telemt_me_refill_failed_total 3067
telemt_me_writer_restored_same_endpoint_total 26823
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 234367
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 3062136253 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 108919494731 (101.44 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 141112.1 (39h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1033803
telemt_connections_bad_total 78577
telemt_handshake_timeouts_total 13121
telemt_upstream_connect_attempt_total 29943
telemt_upstream_connect_success_total 29786
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 29943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15746
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 214
telemt_me_reconnect_attempts_total 26388
telemt_me_reconnect_success_total 22734
telemt_me_reader_eof_total 24270
telemt_me_idle_close_by_peer_total 24269
telemt_me_route_drop_no_conn_total 730829
telemt_me_route_drop_channel_closed_total 145
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1002212
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 767
telemt_desync_full_logged_total 239
telemt_desync_suppressed_total 528
telemt_desync_frames_bucket_total{bucket="1_2"} 189
telemt_desync_frames_bucket_total{bucket="3_10"} 280
telemt_desync_frames_bucket_total{bucket="gt_10"} 298
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 23123
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 22707
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 389
telemt_user_connections_total{user="hello"} 860787
telemt_user_connections_current{user="hello"} 732
telemt_user_octets_from_client{user="hello"} 18207189960 (16.96 GB)
telemt_user_octets_to_client{user="hello"} 489252969156 (455.65 GB)
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 98
```