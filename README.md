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

# Server Metrics 2026-03-16 07:54:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 121186.2 (33h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 558762
telemt_connections_bad_total 5766
telemt_handshake_timeouts_total 19595
telemt_upstream_connect_attempt_total 28366
telemt_upstream_connect_success_total 28233
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 28366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15640
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25677
telemt_me_reconnect_success_total 22242
telemt_me_reader_eof_total 23800
telemt_me_idle_close_by_peer_total 23800
telemt_me_route_drop_no_conn_total 525229
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 555480
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2725
telemt_desync_full_logged_total 1069
telemt_desync_suppressed_total 1656
telemt_desync_frames_bucket_total{bucket="1_2"} 596
telemt_desync_frames_bucket_total{bucket="3_10"} 1047
telemt_desync_frames_bucket_total{bucket="gt_10"} 1082
telemt_pool_swap_total 118
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22596
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 22208
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 354
telemt_user_connections_total{user="hello"} 494298
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 9487221520 (8.84 GB)
telemt_user_octets_to_client{user="hello"} 318316118944 (296.45 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 121193.4 (33h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223508
telemt_connections_bad_total 3156
telemt_handshake_timeouts_total 15090
telemt_upstream_connect_attempt_total 32637
telemt_upstream_connect_success_total 32562
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 32637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17834
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 626
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 33066
telemt_me_reconnect_success_total 26146
telemt_me_reader_eof_total 27991
telemt_me_idle_close_by_peer_total 27990
telemt_me_route_drop_no_conn_total 109413
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197356
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 26718
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 26130
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 572
telemt_user_connections_total{user="hello"} 196901
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 4526568977 (4.22 GB)
telemt_user_octets_to_client{user="hello"} 110721866840 (103.12 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 121186.1 (33h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 241304
telemt_connections_bad_total 5734
telemt_handshake_timeouts_total 4604
telemt_upstream_connect_attempt_total 33656
telemt_upstream_connect_success_total 33648
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 33656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 34991
telemt_me_reconnect_success_total 27588
telemt_me_reader_eof_total 29703
telemt_me_idle_close_by_peer_total 29702
telemt_me_route_drop_no_conn_total 84070
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193122
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 83
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 28086
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 27580
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 498
telemt_user_connections_total{user="hello"} 192832
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 17500049593 (16.30 GB)
telemt_user_octets_to_client{user="hello"} 112397527184 (104.68 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 121185.7 (33h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 332035
telemt_connections_bad_total 1344
telemt_handshake_timeouts_total 2944
telemt_upstream_connect_attempt_total 28045
telemt_upstream_connect_success_total 28013
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 28045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14438
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 22138
telemt_me_reconnect_success_total 22001
telemt_me_reader_eof_total 23492
telemt_me_idle_close_by_peer_total 23491
telemt_me_route_drop_no_conn_total 117096
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305792
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1084
telemt_desync_full_logged_total 376
telemt_desync_suppressed_total 708
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 459
telemt_desync_frames_bucket_total{bucket="gt_10"} 403
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 22289
telemt_me_writer_restored_same_endpoint_total 21990
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 305671
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 4885194090 (4.55 GB)
telemt_user_octets_to_client{user="hello"} 130560813476 (121.59 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 96257.1 (26h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217817
telemt_connections_bad_total 36042
telemt_handshake_timeouts_total 3620
telemt_upstream_connect_attempt_total 27505
telemt_upstream_connect_success_total 27355
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 27505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15094
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 116915
telemt_me_reconnect_success_total 22424
telemt_me_reader_eof_total 23810
telemt_me_idle_close_by_peer_total 23810
telemt_me_route_drop_no_conn_total 68306
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172616
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 517
telemt_desync_full_logged_total 126
telemt_desync_suppressed_total 391
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 225
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 22610
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 22320
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 172240
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 2358377869 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 72864291259 (67.86 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 121186.0 (33h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 796099
telemt_connections_bad_total 69377
telemt_handshake_timeouts_total 7352
telemt_upstream_connect_attempt_total 25470
telemt_upstream_connect_success_total 25335
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 25470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13188
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 20656
telemt_me_reconnect_success_total 19308
telemt_me_reader_eof_total 20621
telemt_me_idle_close_by_peer_total 20621
telemt_me_route_drop_no_conn_total 639830
telemt_me_route_drop_channel_closed_total 107
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 795912
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 19577
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 19281
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 654546
telemt_user_connections_current{user="hello"} 545
telemt_user_octets_from_client{user="hello"} 14458773424 (13.47 GB)
telemt_user_octets_to_client{user="hello"} 394141480680 (367.07 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 87
```