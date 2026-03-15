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

# Server Metrics 2026-03-15 11:18:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 47066.2 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200210
telemt_connections_bad_total 1377
telemt_handshake_timeouts_total 4379
telemt_upstream_connect_attempt_total 11909
telemt_upstream_connect_success_total 11845
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 11909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6553
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 11851
telemt_me_reconnect_success_total 9474
telemt_me_reader_eof_total 10111
telemt_me_idle_close_by_peer_total 10111
telemt_me_route_drop_no_conn_total 417776
telemt_me_route_drop_channel_closed_total 64
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247640
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1458
telemt_desync_full_logged_total 578
telemt_desync_suppressed_total 880
telemt_desync_frames_bucket_total{bucket="1_2"} 239
telemt_desync_frames_bucket_total{bucket="3_10"} 577
telemt_desync_frames_bucket_total{bucket="gt_10"} 642
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9639
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 9443
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 186887
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 3531546548 (3.29 GB)
telemt_user_octets_to_client{user="hello"} 185635703520 (172.89 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 47072.3 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66175
telemt_connections_bad_total 2332
telemt_handshake_timeouts_total 3093
telemt_upstream_connect_attempt_total 12672
telemt_upstream_connect_success_total 12672
telemt_upstream_connect_attempts_per_request{bucket="1"} 12672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12607
telemt_me_reconnect_success_total 10280
telemt_me_reader_eof_total 11034
telemt_me_idle_close_by_peer_total 11034
telemt_me_route_drop_no_conn_total 31266
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58583
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10465
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 10264
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 58582
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 1073722008 (1023.98 MB)
telemt_user_octets_to_client{user="hello"} 24184801760 (22.52 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 47064.8 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74048
telemt_connections_bad_total 1010
telemt_handshake_timeouts_total 2542
telemt_upstream_connect_attempt_total 13281
telemt_upstream_connect_success_total 13273
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 13281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 12092
telemt_me_reconnect_success_total 10884
telemt_me_reader_eof_total 11659
telemt_me_idle_close_by_peer_total 11659
telemt_me_route_drop_no_conn_total 28172
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67305
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 11022
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 10876
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 67223
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 9424070952 (8.78 GB)
telemt_user_octets_to_client{user="hello"} 41485866008 (38.64 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 47064.5 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97530
telemt_connections_bad_total 286
telemt_handshake_timeouts_total 667
telemt_upstream_connect_attempt_total 11138
telemt_upstream_connect_success_total 11137
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5782
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8817
telemt_me_reconnect_success_total 8774
telemt_me_reader_eof_total 9361
telemt_me_idle_close_by_peer_total 9361
telemt_me_route_drop_no_conn_total 39488
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89109
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 206
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 143
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8866
telemt_me_writer_restored_same_endpoint_total 8763
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 89030
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 1672500864 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 52230837820 (48.64 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 22136.0 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40350
telemt_connections_bad_total 4595
telemt_handshake_timeouts_total 792
telemt_upstream_connect_attempt_total 7399
telemt_upstream_connect_success_total 7344
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 7399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 100464
telemt_me_reconnect_success_total 6050
telemt_me_reader_eof_total 6269
telemt_me_idle_close_by_peer_total 6269
telemt_me_route_drop_no_conn_total 17423
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33933
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 67
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 55
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 6033
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 5946
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 34071
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 535350985 (510.55 MB)
telemt_user_octets_to_client{user="hello"} 13789783311 (12.84 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 47063.8 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260010
telemt_connections_bad_total 44952
telemt_handshake_timeouts_total 1986
telemt_upstream_connect_attempt_total 10059
telemt_upstream_connect_success_total 9998
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 10059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_reconnect_attempts_total 7668
telemt_me_reconnect_success_total 7621
telemt_me_reader_eof_total 8122
telemt_me_idle_close_by_peer_total 8122
telemt_me_route_drop_no_conn_total 115202
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205404
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 87
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 7682
telemt_me_writer_restored_same_endpoint_total 7594
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 203771
telemt_user_connections_current{user="hello"} 538
telemt_user_octets_from_client{user="hello"} 4701432440 (4.38 GB)
telemt_user_octets_to_client{user="hello"} 99526547208 (92.69 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 79
```