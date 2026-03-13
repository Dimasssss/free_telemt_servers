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

# Server Metrics 2026-03-13 14:09:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 110141.4 (30h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454838
telemt_connections_bad_total 3216
telemt_handshake_timeouts_total 8517
telemt_upstream_connect_attempt_total 27786
telemt_upstream_connect_success_total 27656
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 27786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2422
telemt_me_reconnect_attempts_total 25662
telemt_me_reconnect_success_total 22132
telemt_me_reader_eof_total 23641
telemt_me_idle_close_by_peer_total 23640
telemt_me_route_drop_no_conn_total 147455
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 397708
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1334
telemt_desync_full_logged_total 472
telemt_desync_suppressed_total 862
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 486
telemt_desync_frames_bucket_total{bucket="gt_10"} 559
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 22471
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 22116
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 339
telemt_user_connections_total{user="hello"} 397287
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 7168240980 (6.68 GB)
telemt_user_octets_to_client{user="hello"} 181903345744 (169.41 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 110034.2 (30h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213890
telemt_connections_bad_total 1776
telemt_handshake_timeouts_total 1534
telemt_upstream_connect_attempt_total 73121
telemt_upstream_connect_success_total 72377
telemt_upstream_connect_fail_total 744
telemt_upstream_connect_attempts_per_request{bucket="1"} 73121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 698
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 744
telemt_me_keepalive_timeout_total 1396
telemt_me_reconnect_attempts_total 106674
telemt_me_reconnect_success_total 26022
telemt_me_reader_eof_total 29302
telemt_me_idle_close_by_peer_total 29302
telemt_me_route_drop_no_conn_total 79968
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161428
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 25
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 28766
telemt_me_refill_failed_total 2516
telemt_me_writer_restored_same_endpoint_total 26005
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2744
telemt_user_connections_total{user="hello"} 202054
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 2046773069 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 65128888420 (60.66 GB)
telemt_user_msgs_from_client{user="hello"} 601478
telemt_user_msgs_to_client{user="hello"} 4159611
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 109998.1 (30h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259753
telemt_connections_bad_total 2111
telemt_handshake_timeouts_total 10785
telemt_upstream_connect_attempt_total 29566
telemt_upstream_connect_success_total 29562
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 29566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15815
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2281
telemt_me_reconnect_attempts_total 25217
telemt_me_reconnect_success_total 24002
telemt_me_reader_eof_total 25721
telemt_me_idle_close_by_peer_total 25721
telemt_me_route_drop_no_conn_total 94422
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 237522
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 24262
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23982
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 260
telemt_user_connections_total{user="hello"} 237442
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 9483232876 (8.83 GB)
telemt_user_octets_to_client{user="hello"} 101526359368 (94.55 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 109973.5 (30h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358105
telemt_connections_bad_total 15040
telemt_handshake_timeouts_total 3440
telemt_upstream_connect_attempt_total 41519
telemt_upstream_connect_success_total 31395
telemt_upstream_connect_fail_total 10124
telemt_upstream_connect_attempts_per_request{bucket="1"} 41519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15303
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 209
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10124
telemt_me_keepalive_timeout_total 4128
telemt_me_reconnect_attempts_total 96657
telemt_me_reconnect_success_total 22829
telemt_me_reader_eof_total 25830
telemt_me_idle_close_by_peer_total 25823
telemt_me_route_drop_no_conn_total 128231
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 309060
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1179
telemt_desync_full_logged_total 349
telemt_desync_suppressed_total 830
telemt_desync_frames_bucket_total{bucket="1_2"} 292
telemt_desync_frames_bucket_total{bucket="3_10"} 442
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 25428
telemt_me_refill_failed_total 2302
telemt_me_writer_restored_same_endpoint_total 22819
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2599
telemt_user_connections_total{user="hello"} 311970
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 6773260126 (6.31 GB)
telemt_user_octets_to_client{user="hello"} 116864009201 (108.84 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 60144.9 (16h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90901
telemt_connections_bad_total 12125
telemt_handshake_timeouts_total 1207
telemt_upstream_connect_attempt_total 25026
telemt_upstream_connect_success_total 24822
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 25026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 1023
telemt_me_reconnect_attempts_total 26831
telemt_me_reconnect_success_total 16911
telemt_me_reader_eof_total 18132
telemt_me_idle_close_by_peer_total 18132
telemt_me_route_drop_no_conn_total 27015
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69772
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 206
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 165
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 17368
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 16893
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 457
telemt_user_connections_total{user="hello"} 74672
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 903817829 (861.95 MB)
telemt_user_octets_to_client{user="hello"} 21700838135 (20.21 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 109929.9 (30h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 643995
telemt_connections_bad_total 17991
telemt_handshake_timeouts_total 19234
telemt_upstream_connect_attempt_total 23167
telemt_upstream_connect_success_total 23049
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 23167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 2511
telemt_me_reconnect_attempts_total 22188
telemt_me_reconnect_success_total 17563
telemt_me_reader_eof_total 18854
telemt_me_idle_close_by_peer_total 18851
telemt_me_route_drop_no_conn_total 311936
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 612187
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 475
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 297
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 17936
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17556
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 373
telemt_user_connections_total{user="hello"} 585133
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 10206197628 (9.51 GB)
telemt_user_octets_to_client{user="hello"} 308734090960 (287.53 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 59
```