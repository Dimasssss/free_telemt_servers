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

# Server Metrics 2026-03-13 17:43:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 122989.3 (34h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 519054
telemt_connections_bad_total 7849
telemt_handshake_timeouts_total 12000
telemt_upstream_connect_attempt_total 30829
telemt_upstream_connect_success_total 30678
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 30829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16695
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3429
telemt_me_reconnect_attempts_total 29165
telemt_me_reconnect_success_total 24526
telemt_me_reader_eof_total 26192
telemt_me_idle_close_by_peer_total 26191
telemt_me_route_drop_no_conn_total 168736
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 451299
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1463
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 957
telemt_desync_frames_bucket_total{bucket="1_2"} 322
telemt_desync_frames_bucket_total{bucket="3_10"} 534
telemt_desync_frames_bucket_total{bucket="gt_10"} 607
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24941
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 24510
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 415
telemt_user_connections_total{user="hello"} 450868
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 8320538624 (7.75 GB)
telemt_user_octets_to_client{user="hello"} 212235282948 (197.66 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 122881.8 (34h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255577
telemt_connections_bad_total 1948
telemt_handshake_timeouts_total 1821
telemt_upstream_connect_attempt_total 109351
telemt_upstream_connect_success_total 108513
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 109351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1563
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_timeout_total 1516
telemt_me_reconnect_attempts_total 125952
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29909
telemt_me_idle_close_by_peer_total 29909
telemt_me_route_drop_no_conn_total 82471
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165848
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 30
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
telemt_me_writer_removed_unexpected_total 29379
telemt_me_refill_failed_total 3118
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3346
telemt_user_connections_total{user="hello"} 241977
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 2526789092 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 74704305853 (69.57 GB)
telemt_user_msgs_from_client{user="hello"} 1198530
telemt_user_msgs_to_client{user="hello"} 7023611
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 122845.7 (34h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301971
telemt_connections_bad_total 2501
telemt_handshake_timeouts_total 17087
telemt_upstream_connect_attempt_total 32798
telemt_upstream_connect_success_total 32794
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 32798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17544
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2612
telemt_me_reconnect_attempts_total 27837
telemt_me_reconnect_success_total 26608
telemt_me_reader_eof_total 28529
telemt_me_idle_close_by_peer_total 28529
telemt_me_route_drop_no_conn_total 107885
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 271760
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 26906
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 26588
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 271669
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 10164871360 (9.47 GB)
telemt_user_octets_to_client{user="hello"} 112157363216 (104.45 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 122821.0 (34h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 408446
telemt_connections_bad_total 15106
telemt_handshake_timeouts_total 3866
telemt_upstream_connect_attempt_total 60074
telemt_upstream_connect_success_total 49827
telemt_upstream_connect_fail_total 10247
telemt_upstream_connect_attempts_per_request{bucket="1"} 60074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 280
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10247
telemt_me_keepalive_timeout_total 4655
telemt_me_reconnect_attempts_total 114310
telemt_me_reconnect_success_total 24655
telemt_me_reader_eof_total 28154
telemt_me_idle_close_by_peer_total 28147
telemt_me_route_drop_no_conn_total 140818
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 340603
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1353
telemt_desync_full_logged_total 403
telemt_desync_suppressed_total 950
telemt_desync_frames_bucket_total{bucket="1_2"} 333
telemt_desync_frames_bucket_total{bucket="3_10"} 521
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 27765
telemt_me_refill_failed_total 2796
telemt_me_writer_restored_same_endpoint_total 24645
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3110
telemt_user_connections_total{user="hello"} 359493
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 8361470795 (7.79 GB)
telemt_user_octets_to_client{user="hello"} 128971600784 (120.11 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 72992.6 (20h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119416
telemt_connections_bad_total 15146
telemt_handshake_timeouts_total 1392
telemt_upstream_connect_attempt_total 28833
telemt_upstream_connect_success_total 28568
telemt_upstream_connect_fail_total 264
telemt_upstream_connect_attempts_per_request{bucket="1"} 28832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14787
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13693
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 264
telemt_me_keepalive_timeout_total 1163
telemt_me_reconnect_attempts_total 33386
telemt_me_reconnect_success_total 19999
telemt_me_reader_eof_total 21453
telemt_me_idle_close_by_peer_total 21453
telemt_me_route_drop_no_conn_total 37241
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94114
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 427
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 340
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 20600
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 19981
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 601
telemt_user_connections_total{user="hello"} 99011
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 1186305817 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 31744540755 (29.56 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 122778.4 (34h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 749995
telemt_connections_bad_total 24693
telemt_handshake_timeouts_total 24427
telemt_upstream_connect_attempt_total 25603
telemt_upstream_connect_success_total 25468
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 25603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 2968
telemt_me_reconnect_attempts_total 24004
telemt_me_reconnect_success_total 19361
telemt_me_reader_eof_total 20779
telemt_me_idle_close_by_peer_total 20776
telemt_me_route_drop_no_conn_total 355132
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 703554
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 680
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 216
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 19760
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19354
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 399
telemt_user_connections_total{user="hello"} 676437
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 11908839484 (11.09 GB)
telemt_user_octets_to_client{user="hello"} 338917490300 (315.64 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 57
```