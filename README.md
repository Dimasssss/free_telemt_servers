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

# Server Metrics 2026-03-13 00:23:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 60611.9 (16h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256333
telemt_connections_bad_total 2753
telemt_handshake_timeouts_total 5284
telemt_upstream_connect_attempt_total 15246
telemt_upstream_connect_success_total 15179
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 15246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1495
telemt_me_reconnect_attempts_total 15579
telemt_me_reconnect_success_total 12107
telemt_me_reader_eof_total 12912
telemt_me_idle_close_by_peer_total 12911
telemt_me_route_drop_no_conn_total 79764
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212234
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 716
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 267
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12351
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 12091
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 212002
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 3891449808 (3.62 GB)
telemt_user_octets_to_client{user="hello"} 108042944100 (100.62 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 60505.2 (16h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118216
telemt_connections_bad_total 687
telemt_handshake_timeouts_total 963
telemt_upstream_connect_attempt_total 34356
telemt_upstream_connect_success_total 33953
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 34356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 500
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_keepalive_timeout_total 426
telemt_me_reconnect_attempts_total 56267
telemt_me_reconnect_success_total 14395
telemt_me_reader_eof_total 16082
telemt_me_idle_close_by_peer_total 16082
telemt_me_route_drop_no_conn_total 42511
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95678
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 15807
telemt_me_refill_failed_total 1307
telemt_me_writer_restored_same_endpoint_total 14380
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1412
telemt_user_connections_total{user="hello"} 112178
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 1226756972 (1.14 GB)
telemt_user_octets_to_client{user="hello"} 34535725835 (32.16 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 60468.6 (16h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143784
telemt_connections_bad_total 1665
telemt_handshake_timeouts_total 2322
telemt_upstream_connect_attempt_total 16634
telemt_upstream_connect_success_total 16632
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 16634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8826
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 352
telemt_me_reconnect_attempts_total 14685
telemt_me_reconnect_success_total 13534
telemt_me_reader_eof_total 14466
telemt_me_idle_close_by_peer_total 14466
telemt_me_route_drop_no_conn_total 54519
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134418
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 13702
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 13514
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 134384
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 2622824644 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 62215079576 (57.94 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 60444.4 (16h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206845
telemt_connections_bad_total 13281
telemt_handshake_timeouts_total 1384
telemt_upstream_connect_attempt_total 28616
telemt_upstream_connect_success_total 18876
telemt_upstream_connect_fail_total 9739
telemt_upstream_connect_attempts_per_request{bucket="1"} 28615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8919
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9739
telemt_me_keepalive_timeout_total 3192
telemt_me_reconnect_attempts_total 46168
telemt_me_reconnect_success_total 12952
telemt_me_reader_eof_total 14449
telemt_me_idle_close_by_peer_total 14442
telemt_me_route_drop_no_conn_total 73755
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170742
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 14188
telemt_me_refill_failed_total 1034
telemt_me_writer_restored_same_endpoint_total 12942
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1236
telemt_user_connections_total{user="hello"} 173496
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 3004656734 (2.80 GB)
telemt_user_octets_to_client{user="hello"} 71374353753 (66.47 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 10616.0 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9554
telemt_connections_bad_total 1960
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 3330
telemt_upstream_connect_success_total 3298
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 3330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1835
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 2757
telemt_me_reconnect_success_total 2751
telemt_me_reader_eof_total 2923
telemt_me_idle_close_by_peer_total 2923
telemt_me_route_drop_no_conn_total 2900
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7240
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2764
telemt_me_writer_restored_same_endpoint_total 2735
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 7240
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 27093416 (25.84 MB)
telemt_user_octets_to_client{user="hello"} 2375214224 (2.21 GB)
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 60400.8 (16h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 343849
telemt_connections_bad_total 6211
telemt_handshake_timeouts_total 2553
telemt_upstream_connect_attempt_total 12759
telemt_upstream_connect_success_total 12689
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 12759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1296
telemt_me_reconnect_attempts_total 13265
telemt_me_reconnect_success_total 9649
telemt_me_reader_eof_total 10346
telemt_me_idle_close_by_peer_total 10344
telemt_me_route_drop_no_conn_total 153735
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336879
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 297
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 112
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 9880
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 9642
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 231
telemt_user_connections_total{user="hello"} 325179
telemt_user_connections_current{user="hello"} 283
telemt_user_octets_from_client{user="hello"} 5572665400 (5.19 GB)
telemt_user_octets_to_client{user="hello"} 175367656244 (163.32 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 30
```