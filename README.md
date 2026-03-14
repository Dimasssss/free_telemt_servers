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

# Server Metrics 2026-03-14 11:52:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 188363.6 (52h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 742134
telemt_connections_bad_total 34646
telemt_handshake_timeouts_total 14397
telemt_upstream_connect_attempt_total 47899
telemt_upstream_connect_success_total 47661
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 47899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6327
telemt_me_reconnect_attempts_total 43649
telemt_me_reconnect_success_total 37882
telemt_me_reader_eof_total 40506
telemt_me_idle_close_by_peer_total 40505
telemt_me_route_drop_no_conn_total 244700
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 636891
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2682
telemt_desync_full_logged_total 896
telemt_desync_suppressed_total 1786
telemt_desync_frames_bucket_total{bucket="1_2"} 556
telemt_desync_frames_bucket_total{bucket="3_10"} 1007
telemt_desync_frames_bucket_total{bucket="gt_10"} 1119
telemt_pool_swap_total 171
telemt_me_writer_removed_unexpected_total 38467
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37862
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 585
telemt_user_connections_total{user="hello"} 636792
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 17694239034 (16.48 GB)
telemt_user_octets_to_client{user="hello"} 306236870712 (285.21 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 188256.5 (52h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368317
telemt_connections_bad_total 2847
telemt_handshake_timeouts_total 3309
telemt_upstream_connect_attempt_total 155878
telemt_upstream_connect_success_total 154488
telemt_upstream_connect_fail_total 1390
telemt_upstream_connect_attempts_per_request{bucket="1"} 155878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39843
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2480
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1390
telemt_me_keepalive_timeout_total 5695
telemt_me_reconnect_attempts_total 195637
telemt_me_reconnect_success_total 41777
telemt_me_reader_eof_total 47664
telemt_me_idle_close_by_peer_total 47664
telemt_me_route_drop_no_conn_total 127393
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244656
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 46982
telemt_me_refill_failed_total 4800
telemt_me_writer_restored_same_endpoint_total 41759
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5205
telemt_user_connections_total{user="hello"} 347752
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 3534859283 (3.29 GB)
telemt_user_octets_to_client{user="hello"} 112029331775 (104.34 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 188220.3 (52h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 425852
telemt_connections_bad_total 3313
telemt_handshake_timeouts_total 36537
telemt_upstream_connect_attempt_total 50244
telemt_upstream_connect_success_total 50235
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 50244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27069
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4285
telemt_me_reconnect_attempts_total 42054
telemt_me_reconnect_success_total 40733
telemt_me_reader_eof_total 43756
telemt_me_idle_close_by_peer_total 43756
telemt_me_route_drop_no_conn_total 155484
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370754
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 146
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 176
telemt_me_writer_removed_unexpected_total 41222
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 40712
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 489
telemt_user_connections_total{user="hello"} 370514
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 15176345002 (14.13 GB)
telemt_user_octets_to_client{user="hello"} 162699069263 (151.53 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 188195.9 (52h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 540113
telemt_connections_bad_total 16774
telemt_handshake_timeouts_total 5292
telemt_upstream_connect_attempt_total 80535
telemt_upstream_connect_success_total 69834
telemt_upstream_connect_fail_total 10701
telemt_upstream_connect_attempts_per_request{bucket="1"} 80535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28841
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 384
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10701
telemt_me_keepalive_timeout_total 5836
telemt_me_reconnect_attempts_total 156051
telemt_me_reconnect_success_total 41409
telemt_me_reader_eof_total 46317
telemt_me_idle_close_by_peer_total 46309
telemt_me_route_drop_no_conn_total 195796
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 463328
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2115
telemt_desync_full_logged_total 622
telemt_desync_suppressed_total 1493
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 819
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 45466
telemt_me_refill_failed_total 3574
telemt_me_writer_restored_same_endpoint_total 41399
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4057
telemt_user_connections_total{user="hello"} 482194
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 10192640791 (9.49 GB)
telemt_user_octets_to_client{user="hello"} 196377363264 (182.89 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 138367.4 (38h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234303
telemt_connections_bad_total 37432
telemt_handshake_timeouts_total 2142
telemt_upstream_connect_attempt_total 48602
telemt_upstream_connect_success_total 48116
telemt_upstream_connect_fail_total 486
telemt_upstream_connect_attempts_per_request{bucket="1"} 48602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23964
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 486
telemt_me_keepalive_timeout_total 3115
telemt_me_reconnect_attempts_total 52231
telemt_me_reconnect_success_total 36342
telemt_me_reader_eof_total 38854
telemt_me_idle_close_by_peer_total 38854
telemt_me_route_drop_no_conn_total 70922
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183587
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 789
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 596
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 287
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 37180
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 36324
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 838
telemt_user_connections_total{user="hello"} 188343
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 2749207177 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 86529320895 (80.59 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 188151.9 (52h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1096986
telemt_connections_bad_total 37679
telemt_handshake_timeouts_total 27167
telemt_upstream_connect_attempt_total 39240
telemt_upstream_connect_success_total 39035
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 39240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_timeout_total 5181
telemt_me_reconnect_attempts_total 34423
telemt_me_reconnect_success_total 29729
telemt_me_reader_eof_total 31875
telemt_me_idle_close_by_peer_total 31872
telemt_me_route_drop_no_conn_total 515112
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1017195
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 809
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 175
telemt_me_writer_removed_unexpected_total 30252
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29722
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 989779
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 21205675424 (19.75 GB)
telemt_user_octets_to_client{user="hello"} 495539192968 (461.51 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 68
```