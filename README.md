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

# Server Metrics 2026-03-15 14:43:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 59318.1 (16h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268199
telemt_connections_bad_total 2490
telemt_handshake_timeouts_total 7352
telemt_upstream_connect_attempt_total 14913
telemt_upstream_connect_success_total 14836
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 14913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8254
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 15259
telemt_me_reconnect_success_total 11879
telemt_me_reader_eof_total 12666
telemt_me_idle_close_by_peer_total 12666
telemt_me_route_drop_no_conn_total 441086
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308783
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1711
telemt_desync_full_logged_total 682
telemt_desync_suppressed_total 1029
telemt_desync_frames_bucket_total{bucket="1_2"} 306
telemt_desync_frames_bucket_total{bucket="3_10"} 670
telemt_desync_frames_bucket_total{bucket="gt_10"} 735
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 12106
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 11848
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 247890
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 5423930020 (5.05 GB)
telemt_user_octets_to_client{user="hello"} 213968058940 (199.27 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 59324.8 (16h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99498
telemt_connections_bad_total 2784
telemt_handshake_timeouts_total 9613
telemt_upstream_connect_attempt_total 16385
telemt_upstream_connect_success_total 16385
telemt_upstream_connect_attempts_per_request{bucket="1"} 16385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9195
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 15743
telemt_me_reconnect_success_total 13390
telemt_me_reader_eof_total 14308
telemt_me_idle_close_by_peer_total 14308
telemt_me_route_drop_no_conn_total 42098
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84066
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 13619
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 13374
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 84057
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 1642831132 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 40069772144 (37.32 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 59318.2 (16h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108531
telemt_connections_bad_total 1649
telemt_handshake_timeouts_total 2793
telemt_upstream_connect_attempt_total 17509
telemt_upstream_connect_success_total 17501
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 17509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9914
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 21842
telemt_me_reconnect_success_total 14502
telemt_me_reader_eof_total 15580
telemt_me_idle_close_by_peer_total 15580
telemt_me_route_drop_no_conn_total 40760
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93512
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 14864
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 14494
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 93413
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 10171333564 (9.47 GB)
telemt_user_octets_to_client{user="hello"} 54607166248 (50.86 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 59317.1 (16h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143091
telemt_connections_bad_total 792
telemt_handshake_timeouts_total 921
telemt_upstream_connect_attempt_total 14245
telemt_upstream_connect_success_total 14241
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 14245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 11351
telemt_me_reconnect_success_total 11281
telemt_me_reader_eof_total 11989
telemt_me_idle_close_by_peer_total 11989
telemt_me_route_drop_no_conn_total 55717
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130853
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 458
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 313
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 11412
telemt_me_writer_restored_same_endpoint_total 11270
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 130770
telemt_user_connections_current{user="hello"} 248
telemt_user_octets_from_client{user="hello"} 2464789852 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 64295107016 (59.88 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 34388.5 (9h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82916
telemt_connections_bad_total 21467
telemt_handshake_timeouts_total 1425
telemt_upstream_connect_attempt_total 10847
telemt_upstream_connect_success_total 10780
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 10847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 103283
telemt_me_reconnect_success_total 8853
telemt_me_reader_eof_total 9258
telemt_me_idle_close_by_peer_total 9258
telemt_me_route_drop_no_conn_total 28351
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58132
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 155
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 8873
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 8749
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 58269
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 852794241 (813.29 MB)
telemt_user_octets_to_client{user="hello"} 23338188939 (21.74 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 59316.3 (16h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359276
telemt_connections_bad_total 48511
telemt_handshake_timeouts_total 3002
telemt_upstream_connect_attempt_total 12708
telemt_upstream_connect_success_total 12632
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 10943
telemt_me_reconnect_success_total 9656
telemt_me_reader_eof_total 10290
telemt_me_idle_close_by_peer_total 10290
telemt_me_route_drop_no_conn_total 167470
telemt_me_route_drop_channel_closed_total 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 297033
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 47
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 9788
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 9629
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 294879
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 7401282124 (6.89 GB)
telemt_user_octets_to_client{user="hello"} 149275320668 (139.02 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 80
```