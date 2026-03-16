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

# Server Metrics 2026-03-16 03:44:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 106172.1 (29h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454606
telemt_connections_bad_total 5373
telemt_handshake_timeouts_total 15529
telemt_upstream_connect_attempt_total 25358
telemt_upstream_connect_success_total 25242
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 25358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14040
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 23420
telemt_me_reconnect_success_total 19997
telemt_me_reader_eof_total 21382
telemt_me_idle_close_by_peer_total 21382
telemt_me_route_drop_no_conn_total 501445
telemt_me_route_drop_channel_closed_total 81
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 476830
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2318
telemt_desync_full_logged_total 933
telemt_desync_suppressed_total 1385
telemt_desync_frames_bucket_total{bucket="1_2"} 464
telemt_desync_frames_bucket_total{bucket="3_10"} 909
telemt_desync_frames_bucket_total{bucket="gt_10"} 945
telemt_pool_swap_total 101
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20320
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 19963
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 415684
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 8520597420 (7.94 GB)
telemt_user_octets_to_client{user="hello"} 294586152408 (274.35 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 106178.4 (29h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184243
telemt_connections_bad_total 2971
telemt_handshake_timeouts_total 14654
telemt_upstream_connect_attempt_total 28915
telemt_upstream_connect_success_total 28840
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 28915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15692
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 30089
telemt_me_reconnect_success_total 23182
telemt_me_reader_eof_total 24832
telemt_me_idle_close_by_peer_total 24831
telemt_me_route_drop_no_conn_total 93379
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159937
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 23723
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 23166
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 541
telemt_user_connections_total{user="hello"} 159483
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 3477654021 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 82878545912 (77.19 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 106171.0 (29h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203905
telemt_connections_bad_total 3023
telemt_handshake_timeouts_total 3992
telemt_upstream_connect_attempt_total 29974
telemt_upstream_connect_success_total 29966
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 29974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 32048
telemt_me_reconnect_success_total 24658
telemt_me_reader_eof_total 26554
telemt_me_idle_close_by_peer_total 26553
telemt_me_route_drop_no_conn_total 72578
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162625
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
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 25133
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 24650
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 475
telemt_user_connections_total{user="hello"} 162358
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 16433582529 (15.30 GB)
telemt_user_octets_to_client{user="hello"} 101698114264 (94.71 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 106170.8 (29h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268817
telemt_connections_bad_total 1227
telemt_handshake_timeouts_total 1700
telemt_upstream_connect_attempt_total 24869
telemt_upstream_connect_success_total 24848
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 24869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12826
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 19716
telemt_me_reconnect_success_total 19600
telemt_me_reader_eof_total 20923
telemt_me_idle_close_by_peer_total 20922
telemt_me_route_drop_no_conn_total 99066
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248549
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 884
telemt_desync_full_logged_total 314
telemt_desync_suppressed_total 570
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 384
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 19840
telemt_me_writer_restored_same_endpoint_total 19589
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 248431
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 4256465304 (3.96 GB)
telemt_user_octets_to_client{user="hello"} 112477420444 (104.75 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 81242.2 (22h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 178270
telemt_connections_bad_total 31467
telemt_handshake_timeouts_total 3131
telemt_upstream_connect_attempt_total 23173
telemt_upstream_connect_success_total 23044
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 23173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 113300
telemt_me_reconnect_success_total 18829
telemt_me_reader_eof_total 20001
telemt_me_idle_close_by_peer_total 20001
telemt_me_route_drop_no_conn_total 56511
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139326
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 18977
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 18725
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 138962
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 1949352901 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 60630346235 (56.47 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 106170.0 (29h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 681289
telemt_connections_bad_total 58743
telemt_handshake_timeouts_total 5062
telemt_upstream_connect_attempt_total 22551
telemt_upstream_connect_success_total 22432
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 22551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 18490
telemt_me_reconnect_success_total 17157
telemt_me_reader_eof_total 18308
telemt_me_idle_close_by_peer_total 18308
telemt_me_route_drop_no_conn_total 596769
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 705474
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
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 17397
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 17130
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 564158
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 13033718744 (12.14 GB)
telemt_user_octets_to_client{user="hello"} 348349122264 (324.43 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 45
```