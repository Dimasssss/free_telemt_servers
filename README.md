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

# Server Metrics 2026-03-15 11:54:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 49211.3 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212374
telemt_connections_bad_total 1392
telemt_handshake_timeouts_total 4589
telemt_upstream_connect_attempt_total 12513
telemt_upstream_connect_success_total 12446
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 12513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6920
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 13355
telemt_me_reconnect_success_total 9985
telemt_me_reader_eof_total 10674
telemt_me_idle_close_by_peer_total 10674
telemt_me_route_drop_no_conn_total 421941
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259083
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1493
telemt_desync_full_logged_total 595
telemt_desync_suppressed_total 898
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 656
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 10189
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 9954
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 198340
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 3719378296 (3.46 GB)
telemt_user_octets_to_client{user="hello"} 189918809912 (176.88 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 49217.6 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72644
telemt_connections_bad_total 2360
telemt_handshake_timeouts_total 4313
telemt_upstream_connect_attempt_total 13436
telemt_upstream_connect_success_total 13436
telemt_upstream_connect_attempts_per_request{bucket="1"} 13436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7573
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 13282
telemt_me_reconnect_success_total 10949
telemt_me_reader_eof_total 11739
telemt_me_idle_close_by_peer_total 11739
telemt_me_route_drop_no_conn_total 33345
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63558
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 11140
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 10933
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 63557
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 1156402424 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 26536874784 (24.71 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 49210.1 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78390
telemt_connections_bad_total 1013
telemt_handshake_timeouts_total 2564
telemt_upstream_connect_attempt_total 14048
telemt_upstream_connect_success_total 14040
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 14048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 13696
telemt_me_reconnect_success_total 11558
telemt_me_reader_eof_total 12393
telemt_me_idle_close_by_peer_total 12393
telemt_me_route_drop_no_conn_total 29980
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71419
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
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
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 11736
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 11550
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 71336
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 9518741692 (8.87 GB)
telemt_user_octets_to_client{user="hello"} 43552098504 (40.56 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 49209.7 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106064
telemt_connections_bad_total 364
telemt_handshake_timeouts_total 696
telemt_upstream_connect_attempt_total 11586
telemt_upstream_connect_success_total 11585
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9178
telemt_me_reconnect_success_total 9132
telemt_me_reader_eof_total 9744
telemt_me_idle_close_by_peer_total 9744
telemt_me_route_drop_no_conn_total 42204
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96752
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 243
telemt_desync_full_logged_total 74
telemt_desync_suppressed_total 169
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 9231
telemt_me_writer_restored_same_endpoint_total 9121
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 96672
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 1726197264 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 54365611060 (50.63 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 24281.3 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55218
telemt_connections_bad_total 14685
telemt_handshake_timeouts_total 850
telemt_upstream_connect_attempt_total 7965
telemt_upstream_connect_success_total 7907
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 7965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 100941
telemt_me_reconnect_success_total 6526
telemt_me_reader_eof_total 6785
telemt_me_idle_close_by_peer_total 6785
telemt_me_route_drop_no_conn_total 19366
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38443
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 82
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 67
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 6514
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 6422
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 38580
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 565180285 (539.00 MB)
telemt_user_octets_to_client{user="hello"} 15032036699 (14.00 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 49209.1 (13h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279023
telemt_connections_bad_total 47658
telemt_handshake_timeouts_total 2051
telemt_upstream_connect_attempt_total 10427
telemt_upstream_connect_success_total 10364
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 10427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_reconnect_attempts_total 7946
telemt_me_reconnect_success_total 7896
telemt_me_reader_eof_total 8405
telemt_me_idle_close_by_peer_total 8405
telemt_me_route_drop_no_conn_total 123484
telemt_me_route_drop_channel_closed_total 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221136
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 124
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7960
telemt_me_writer_restored_same_endpoint_total 7869
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 219498
telemt_user_connections_current{user="hello"} 562
telemt_user_octets_from_client{user="hello"} 4845623204 (4.51 GB)
telemt_user_octets_to_client{user="hello"} 104970505564 (97.76 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 78
```