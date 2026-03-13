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

# Server Metrics 2026-03-13 04:59:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 77188.8 (21h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293799
telemt_connections_bad_total 3058
telemt_handshake_timeouts_total 5860
telemt_upstream_connect_attempt_total 19491
telemt_upstream_connect_success_total 19400
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 19491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1560
telemt_me_reconnect_attempts_total 19024
telemt_me_reconnect_success_total 15527
telemt_me_reader_eof_total 16598
telemt_me_idle_close_by_peer_total 16597
telemt_me_route_drop_no_conn_total 91593
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246898
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 845
telemt_desync_full_logged_total 314
telemt_desync_suppressed_total 531
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 310
telemt_desync_frames_bucket_total{bucket="gt_10"} 368
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 15803
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 15511
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 276
telemt_user_connections_total{user="hello"} 246836
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 4254754684 (3.96 GB)
telemt_user_octets_to_client{user="hello"} 121211611256 (112.89 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 77081.8 (21h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134705
telemt_connections_bad_total 754
telemt_handshake_timeouts_total 1009
telemt_upstream_connect_attempt_total 41278
telemt_upstream_connect_success_total 40760
telemt_upstream_connect_fail_total 517
telemt_upstream_connect_attempts_per_request{bucket="1"} 41277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15867
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 508
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 517
telemt_me_keepalive_timeout_total 564
telemt_me_reconnect_attempts_total 66969
telemt_me_reconnect_success_total 20405
telemt_me_reader_eof_total 22475
telemt_me_idle_close_by_peer_total 22475
telemt_me_route_drop_no_conn_total 49822
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111477
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
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
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 22021
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 20390
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1616
telemt_user_connections_total{user="hello"} 127977
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 1330252428 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 38698760535 (36.04 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 77045.3 (21h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162658
telemt_connections_bad_total 1859
telemt_handshake_timeouts_total 2637
telemt_upstream_connect_attempt_total 21269
telemt_upstream_connect_success_total 21267
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 21269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11442
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 449
telemt_me_reconnect_attempts_total 18539
telemt_me_reconnect_success_total 17375
telemt_me_reader_eof_total 18608
telemt_me_idle_close_by_peer_total 18608
telemt_me_route_drop_no_conn_total 62756
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152145
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 17565
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 17355
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 152072
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 2890957112 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 70737053472 (65.88 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 77021.0 (21h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 234557
telemt_connections_bad_total 13551
telemt_handshake_timeouts_total 1537
telemt_upstream_connect_attempt_total 33662
telemt_upstream_connect_success_total 23778
telemt_upstream_connect_fail_total 9884
telemt_upstream_connect_attempts_per_request{bucket="1"} 33662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11629
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9884
telemt_me_keepalive_timeout_total 3314
telemt_me_reconnect_attempts_total 65843
telemt_me_reconnect_success_total 17065
telemt_me_reader_eof_total 19112
telemt_me_idle_close_by_peer_total 19105
telemt_me_route_drop_no_conn_total 85505
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196456
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 520
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 372
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 195
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 18813
telemt_me_refill_failed_total 1520
telemt_me_writer_restored_same_endpoint_total 17055
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1748
telemt_user_connections_total{user="hello"} 199204
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 3261586822 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 79700764173 (74.23 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 27192.6 (7h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28041
telemt_connections_bad_total 5076
telemt_handshake_timeouts_total 108
telemt_upstream_connect_attempt_total 8685
telemt_upstream_connect_success_total 8599
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 8685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 206
telemt_me_reconnect_attempts_total 7240
telemt_me_reconnect_success_total 7214
telemt_me_reader_eof_total 7700
telemt_me_idle_close_by_peer_total 7700
telemt_me_route_drop_no_conn_total 7737
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22076
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7281
telemt_me_writer_restored_same_endpoint_total 7196
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 22076
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 153187208 (146.09 MB)
telemt_user_octets_to_client{user="hello"} 9220548156 (8.59 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 76977.4 (21h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 394536
telemt_connections_bad_total 7717
telemt_handshake_timeouts_total 2957
telemt_upstream_connect_attempt_total 16407
telemt_upstream_connect_success_total 16315
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 16407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 1434
telemt_me_reconnect_attempts_total 16112
telemt_me_reconnect_success_total 12483
telemt_me_reader_eof_total 13406
telemt_me_idle_close_by_peer_total 13403
telemt_me_route_drop_no_conn_total 176305
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 384603
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 12756
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12476
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 273
telemt_user_connections_total{user="hello"} 372846
telemt_user_connections_current{user="hello"} 283
telemt_user_octets_from_client{user="hello"} 6179762200 (5.76 GB)
telemt_user_octets_to_client{user="hello"} 219847259824 (204.75 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 41
```