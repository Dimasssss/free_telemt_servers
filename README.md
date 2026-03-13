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

# Server Metrics 2026-03-13 05:56:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 80567.1 (22h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305325
telemt_connections_bad_total 3077
telemt_handshake_timeouts_total 6267
telemt_upstream_connect_attempt_total 20294
telemt_upstream_connect_success_total 20197
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 20294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1580
telemt_me_reconnect_attempts_total 19645
telemt_me_reconnect_success_total 16145
telemt_me_reader_eof_total 17256
telemt_me_idle_close_by_peer_total 17255
telemt_me_route_drop_no_conn_total 95215
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257604
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 890
telemt_desync_full_logged_total 330
telemt_desync_suppressed_total 560
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 324
telemt_desync_frames_bucket_total{bucket="gt_10"} 390
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 16429
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 16129
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 284
telemt_user_connections_total{user="hello"} 257540
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 4394229252 (4.09 GB)
telemt_user_octets_to_client{user="hello"} 124466167620 (115.92 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 80459.8 (22h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139397
telemt_connections_bad_total 762
telemt_handshake_timeouts_total 1043
telemt_upstream_connect_attempt_total 42542
telemt_upstream_connect_success_total 41996
telemt_upstream_connect_fail_total 546
telemt_upstream_connect_attempts_per_request{bucket="1"} 42542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16538
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 508
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 546
telemt_me_keepalive_timeout_total 594
telemt_me_reconnect_attempts_total 69342
telemt_me_reconnect_success_total 21465
telemt_me_reader_eof_total 23613
telemt_me_idle_close_by_peer_total 23613
telemt_me_route_drop_no_conn_total 52502
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115985
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
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
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 23128
telemt_me_refill_failed_total 1494
telemt_me_writer_restored_same_endpoint_total 21450
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1663
telemt_user_connections_total{user="hello"} 132482
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 1379783112 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 40037978211 (37.29 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 80423.3 (22h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169080
telemt_connections_bad_total 1908
telemt_handshake_timeouts_total 2745
telemt_upstream_connect_attempt_total 22147
telemt_upstream_connect_success_total 22145
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11933
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 466
telemt_me_reconnect_attempts_total 19244
telemt_me_reconnect_success_total 18075
telemt_me_reader_eof_total 19376
telemt_me_idle_close_by_peer_total 19376
telemt_me_route_drop_no_conn_total 65472
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158131
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
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 18272
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 18055
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 158058
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 2929255412 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 71883375060 (66.95 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 80399.1 (22h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243876
telemt_connections_bad_total 13609
telemt_handshake_timeouts_total 1818
telemt_upstream_connect_attempt_total 34340
telemt_upstream_connect_success_total 24427
telemt_upstream_connect_fail_total 9913
telemt_upstream_connect_attempts_per_request{bucket="1"} 34340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11947
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9913
telemt_me_keepalive_timeout_total 3317
telemt_me_reconnect_attempts_total 69072
telemt_me_reconnect_success_total 17538
telemt_me_reader_eof_total 19681
telemt_me_idle_close_by_peer_total 19674
telemt_me_route_drop_no_conn_total 89010
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204800
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 579
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 411
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 19374
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 17528
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1836
telemt_user_connections_total{user="hello"} 207542
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 3313511786 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 81763293661 (76.15 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 30570.8 (8h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33022
telemt_connections_bad_total 5734
telemt_handshake_timeouts_total 137
telemt_upstream_connect_attempt_total 10327
telemt_upstream_connect_success_total 10226
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 10327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 247
telemt_me_reconnect_attempts_total 9665
telemt_me_reconnect_success_total 8704
telemt_me_reader_eof_total 9274
telemt_me_idle_close_by_peer_total 9274
telemt_me_route_drop_no_conn_total 9311
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26276
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 8815
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 8686
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 26276
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 205250980 (195.74 MB)
telemt_user_octets_to_client{user="hello"} 9576237776 (8.92 GB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 80355.6 (22h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411967
telemt_connections_bad_total 8030
telemt_handshake_timeouts_total 3114
telemt_upstream_connect_attempt_total 17153
telemt_upstream_connect_success_total 17059
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 17153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 1451
telemt_me_reconnect_attempts_total 16682
telemt_me_reconnect_success_total 13050
telemt_me_reader_eof_total 14018
telemt_me_idle_close_by_peer_total 14015
telemt_me_route_drop_no_conn_total 182997
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 399641
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 343
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 211
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 13328
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13043
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 387887
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 6387188204 (5.95 GB)
telemt_user_octets_to_client{user="hello"} 229358302084 (213.61 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 37
```