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

# Server Metrics 2026-03-14 13:09:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 192947.1 (53h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 768248
telemt_connections_bad_total 37101
telemt_handshake_timeouts_total 14603
telemt_upstream_connect_attempt_total 48848
telemt_upstream_connect_success_total 48604
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 48848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26186
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6362
telemt_me_reconnect_attempts_total 44373
telemt_me_reconnect_success_total 38600
telemt_me_reader_eof_total 41268
telemt_me_idle_close_by_peer_total 41267
telemt_me_route_drop_no_conn_total 252759
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 658971
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2887
telemt_desync_full_logged_total 963
telemt_desync_suppressed_total 1924
telemt_desync_frames_bucket_total{bucket="1_2"} 588
telemt_desync_frames_bucket_total{bucket="3_10"} 1096
telemt_desync_frames_bucket_total{bucket="gt_10"} 1203
telemt_pool_swap_total 176
telemt_me_writer_removed_unexpected_total 39194
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 38580
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 594
telemt_user_connections_total{user="hello"} 658875
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 18184574502 (16.94 GB)
telemt_user_octets_to_client{user="hello"} 312540545424 (291.08 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 192840.6 (53h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378635
telemt_connections_bad_total 2881
telemt_handshake_timeouts_total 3389
telemt_upstream_connect_attempt_total 159028
telemt_upstream_connect_success_total 157611
telemt_upstream_connect_fail_total 1417
telemt_upstream_connect_attempts_per_request{bucket="1"} 159028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 114224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40846
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2540
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1417
telemt_me_keepalive_timeout_total 5747
telemt_me_reconnect_attempts_total 199642
telemt_me_reconnect_success_total 42878
telemt_me_reader_eof_total 48884
telemt_me_idle_close_by_peer_total 48884
telemt_me_route_drop_no_conn_total 130889
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251822
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 48
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
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 48196
telemt_me_refill_failed_total 4890
telemt_me_writer_restored_same_endpoint_total 42859
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5318
telemt_user_connections_total{user="hello"} 356715
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 3641206187 (3.39 GB)
telemt_user_octets_to_client{user="hello"} 114183883246 (106.34 GB)
telemt_user_msgs_from_client{user="hello"} 1713995
telemt_user_msgs_to_client{user="hello"} 9567945
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 192804.3 (53h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 435614
telemt_connections_bad_total 3338
telemt_handshake_timeouts_total 36825
telemt_upstream_connect_attempt_total 51843
telemt_upstream_connect_success_total 51834
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 51843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27884
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4385
telemt_me_reconnect_attempts_total 44160
telemt_me_reconnect_success_total 42098
telemt_me_reader_eof_total 45193
telemt_me_idle_close_by_peer_total 45193
telemt_me_route_drop_no_conn_total 160090
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 379741
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 147
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 42622
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 42077
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 524
telemt_user_connections_total{user="hello"} 379468
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 16293802594 (15.17 GB)
telemt_user_octets_to_client{user="hello"} 171615430515 (159.83 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 192779.9 (53h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 556753
telemt_connections_bad_total 16789
telemt_handshake_timeouts_total 5392
telemt_upstream_connect_attempt_total 81814
telemt_upstream_connect_success_total 71066
telemt_upstream_connect_fail_total 10748
telemt_upstream_connect_attempts_per_request{bucket="1"} 81814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 394
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10748
telemt_me_keepalive_timeout_total 5882
telemt_me_reconnect_attempts_total 162551
telemt_me_reconnect_success_total 42402
telemt_me_reader_eof_total 47489
telemt_me_idle_close_by_peer_total 47481
telemt_me_route_drop_no_conn_total 201082
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 478056
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2229
telemt_desync_full_logged_total 657
telemt_desync_suppressed_total 1572
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 843
telemt_desync_frames_bucket_total{bucket="gt_10"} 865
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 46639
telemt_me_refill_failed_total 3746
telemt_me_writer_restored_same_endpoint_total 42392
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4237
telemt_user_connections_total{user="hello"} 496914
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 10442000787 (9.72 GB)
telemt_user_octets_to_client{user="hello"} 206273357616 (192.11 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 142951.3 (39h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244479
telemt_connections_bad_total 39033
telemt_handshake_timeouts_total 2242
telemt_upstream_connect_attempt_total 50131
telemt_upstream_connect_success_total 49622
telemt_upstream_connect_fail_total 509
telemt_upstream_connect_attempts_per_request{bucket="1"} 50131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24764
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 509
telemt_me_keepalive_timeout_total 3163
telemt_me_reconnect_attempts_total 59883
telemt_me_reconnect_success_total 37625
telemt_me_reader_eof_total 40343
telemt_me_idle_close_by_peer_total 40343
telemt_me_route_drop_no_conn_total 74864
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191690
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 874
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 668
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 329
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 38669
telemt_me_refill_failed_total 691
telemt_me_writer_restored_same_endpoint_total 37607
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 1044
telemt_user_connections_total{user="hello"} 196441
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 2816025277 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 89622795715 (83.47 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 192736.1 (53h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1129615
telemt_connections_bad_total 38123
telemt_handshake_timeouts_total 27487
telemt_upstream_connect_attempt_total 40163
telemt_upstream_connect_success_total 39952
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 40163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20960
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 5270
telemt_me_reconnect_attempts_total 35093
telemt_me_reconnect_success_total 30393
telemt_me_reader_eof_total 32572
telemt_me_idle_close_by_peer_total 32569
telemt_me_route_drop_no_conn_total 532739
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1047761
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 817
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 547
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 286
telemt_pool_swap_total 179
telemt_me_writer_removed_unexpected_total 30923
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 30386
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 530
telemt_user_connections_total{user="hello"} 1020380
telemt_user_connections_current{user="hello"} 485
telemt_user_octets_from_client{user="hello"} 21887053336 (20.38 GB)
telemt_user_octets_to_client{user="hello"} 517031765076 (481.52 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 68
```