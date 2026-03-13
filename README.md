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

# Server Metrics 2026-03-13 22:53:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 141625.8 (39h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 580588
telemt_connections_bad_total 18296
telemt_handshake_timeouts_total 12825
telemt_upstream_connect_attempt_total 35984
telemt_upstream_connect_success_total 35802
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 35984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5136
telemt_me_reconnect_attempts_total 32995
telemt_me_reconnect_success_total 28333
telemt_me_reader_eof_total 30268
telemt_me_idle_close_by_peer_total 30267
telemt_me_route_drop_no_conn_total 191347
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 498880
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1600
telemt_desync_full_logged_total 542
telemt_desync_suppressed_total 1058
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 601
telemt_desync_frames_bucket_total{bucket="gt_10"} 656
telemt_pool_swap_total 127
telemt_me_writer_removed_unexpected_total 28797
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 28317
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 498774
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 15298498070 (14.25 GB)
telemt_user_octets_to_client{user="hello"} 247992854768 (230.96 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 141518.6 (39h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296739
telemt_connections_bad_total 2157
telemt_handshake_timeouts_total 1920
telemt_upstream_connect_attempt_total 139924
telemt_upstream_connect_success_total 138889
telemt_upstream_connect_fail_total 1035
telemt_upstream_connect_attempts_per_request{bucket="1"} 139924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1035
telemt_me_keepalive_timeout_total 3716
telemt_me_reconnect_attempts_total 149193
telemt_me_reconnect_success_total 28495
telemt_me_reader_eof_total 33036
telemt_me_idle_close_by_peer_total 33036
telemt_me_route_drop_no_conn_total 89693
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 178300
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 36
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
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 32531
telemt_me_refill_failed_total 3766
telemt_me_writer_restored_same_endpoint_total 28478
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4036
telemt_user_connections_total{user="hello"} 281412
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 2966804567 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 87266637959 (81.27 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 141482.4 (39h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345983
telemt_connections_bad_total 2699
telemt_handshake_timeouts_total 29627
telemt_upstream_connect_attempt_total 37627
telemt_upstream_connect_success_total 37622
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 37627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20268
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2869
telemt_me_reconnect_attempts_total 31755
telemt_me_reconnect_success_total 30507
telemt_me_reader_eof_total 32749
telemt_me_idle_close_by_peer_total 32749
telemt_me_route_drop_no_conn_total 122649
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 301590
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 131
telemt_me_writer_removed_unexpected_total 30854
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 30487
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 347
telemt_user_connections_total{user="hello"} 301491
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 12365817612 (11.52 GB)
telemt_user_octets_to_client{user="hello"} 124908825724 (116.33 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 141457.8 (39h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 448977
telemt_connections_bad_total 15323
telemt_handshake_timeouts_total 4239
telemt_upstream_connect_attempt_total 65077
telemt_upstream_connect_success_total 54692
telemt_upstream_connect_fail_total 10385
telemt_upstream_connect_attempts_per_request{bucket="1"} 65077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20446
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 313
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10385
telemt_me_keepalive_timeout_total 4972
telemt_me_reconnect_attempts_total 131057
telemt_me_reconnect_success_total 28584
telemt_me_reader_eof_total 32598
telemt_me_idle_close_by_peer_total 32591
telemt_me_route_drop_no_conn_total 156912
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 379362
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1649
telemt_desync_full_logged_total 483
telemt_desync_suppressed_total 1166
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 629
telemt_desync_frames_bucket_total{bucket="gt_10"} 634
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 32144
telemt_me_refill_failed_total 3196
telemt_me_writer_restored_same_endpoint_total 28574
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3560
telemt_user_connections_total{user="hello"} 398204
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 8999745319 (8.38 GB)
telemt_user_octets_to_client{user="hello"} 151774280060 (141.35 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 91629.5 (25h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153515
telemt_connections_bad_total 22794
telemt_handshake_timeouts_total 1538
telemt_upstream_connect_attempt_total 33943
telemt_upstream_connect_success_total 33629
telemt_upstream_connect_fail_total 314
telemt_upstream_connect_attempts_per_request{bucket="1"} 33943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 314
telemt_me_keepalive_timeout_total 1318
telemt_me_reconnect_attempts_total 37575
telemt_me_reconnect_success_total 24174
telemt_me_reader_eof_total 25879
telemt_me_idle_close_by_peer_total 25879
telemt_me_route_drop_no_conn_total 46637
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119570
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 24822
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 24156
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 648
telemt_user_connections_total{user="hello"} 124451
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 1473230525 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 58260368823 (54.26 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 141414.0 (39h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 847527
telemt_connections_bad_total 27192
telemt_handshake_timeouts_total 25137
telemt_upstream_connect_attempt_total 29042
telemt_upstream_connect_success_total 28889
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 29042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15348
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 3317
telemt_me_reconnect_attempts_total 26512
telemt_me_reconnect_success_total 21855
telemt_me_reader_eof_total 23441
telemt_me_idle_close_by_peer_total 23438
telemt_me_route_drop_no_conn_total 404398
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 793412
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 219
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 22289
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21848
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 434
telemt_user_connections_total{user="hello"} 766266
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 13219190036 (12.31 GB)
telemt_user_octets_to_client{user="hello"} 388399736992 (361.73 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 27
```