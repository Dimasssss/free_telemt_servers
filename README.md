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

# Server Metrics 2026-03-15 09:31:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 40636.0 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158071
telemt_connections_bad_total 1151
telemt_handshake_timeouts_total 3885
telemt_upstream_connect_attempt_total 10021
telemt_upstream_connect_success_total 9964
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 10021
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5517
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 9135
telemt_me_reconnect_success_total 7920
telemt_me_reader_eof_total 8476
telemt_me_idle_close_by_peer_total 8476
telemt_me_route_drop_no_conn_total 337879
telemt_me_route_drop_channel_closed_total 48
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199889
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1204
telemt_desync_full_logged_total 488
telemt_desync_suppressed_total 716
telemt_desync_frames_bucket_total{bucket="1_2"} 201
telemt_desync_frames_bucket_total{bucket="3_10"} 483
telemt_desync_frames_bucket_total{bucket="gt_10"} 520
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 8030
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 7889
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 147189
telemt_user_connections_current{user="hello"} 390
telemt_user_octets_from_client{user="hello"} 2093548912 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 153239699088 (142.72 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 40643.2 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51073
telemt_connections_bad_total 2114
telemt_handshake_timeouts_total 2954
telemt_upstream_connect_attempt_total 10986
telemt_upstream_connect_success_total 10985
telemt_upstream_connect_attempts_per_request{bucket="1"} 10985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11234
telemt_me_reconnect_success_total 8915
telemt_me_reader_eof_total 9590
telemt_me_idle_close_by_peer_total 9590
telemt_me_route_drop_no_conn_total 24629
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44349
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9080
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 8899
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 44349
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 927300748 (884.34 MB)
telemt_user_octets_to_client{user="hello"} 17366818108 (16.17 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 40635.8 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58233
telemt_connections_bad_total 503
telemt_handshake_timeouts_total 2021
telemt_upstream_connect_attempt_total 10889
telemt_upstream_connect_success_total 10888
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6100
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8872
telemt_me_reconnect_success_total 8827
telemt_me_reader_eof_total 9514
telemt_me_idle_close_by_peer_total 9514
telemt_me_route_drop_no_conn_total 21600
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53285
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 26
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8911
telemt_me_writer_restored_same_endpoint_total 8823
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 53214
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 9218206540 (8.59 GB)
telemt_user_octets_to_client{user="hello"} 35118015440 (32.71 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 40635.5 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73808
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 436
telemt_upstream_connect_attempt_total 9665
telemt_upstream_connect_success_total 9664
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7655
telemt_me_reconnect_success_total 7623
telemt_me_reader_eof_total 8143
telemt_me_idle_close_by_peer_total 8143
telemt_me_route_drop_no_conn_total 31453
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67094
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 136
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 95
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7701
telemt_me_writer_restored_same_endpoint_total 7612
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 67026
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 1309862072 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 41971551344 (39.09 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 15706.9 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25596
telemt_connections_bad_total 2967
telemt_handshake_timeouts_total 352
telemt_upstream_connect_attempt_total 5405
telemt_upstream_connect_success_total 5357
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 5405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_reconnect_attempts_total 98787
telemt_me_reconnect_success_total 4381
telemt_me_reader_eof_total 4521
telemt_me_idle_close_by_peer_total 4521
telemt_me_route_drop_no_conn_total 8194
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21603
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 39
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 4344
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 4277
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 21743
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 202077161 (192.72 MB)
telemt_user_octets_to_client{user="hello"} 11134957659 (10.37 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 40634.7 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187132
telemt_connections_bad_total 22753
telemt_handshake_timeouts_total 1127
telemt_upstream_connect_attempt_total 8712
telemt_upstream_connect_success_total 8661
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 8712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 6644
telemt_me_reconnect_success_total 6609
telemt_me_reader_eof_total 7050
telemt_me_idle_close_by_peer_total 7050
telemt_me_route_drop_no_conn_total 89407
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158218
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 48
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6651
telemt_me_writer_restored_same_endpoint_total 6582
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 156758
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 4139909720 (3.86 GB)
telemt_user_octets_to_client{user="hello"} 80003431044 (74.51 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 57
```