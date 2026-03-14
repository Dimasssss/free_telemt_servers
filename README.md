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

# Server Metrics 2026-03-14 11:32:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 187142.8 (51h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 735900
telemt_connections_bad_total 34419
telemt_handshake_timeouts_total 14351
telemt_upstream_connect_attempt_total 47619
telemt_upstream_connect_success_total 47384
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 47619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6144
telemt_me_reconnect_attempts_total 43458
telemt_me_reconnect_success_total 37693
telemt_me_reader_eof_total 40294
telemt_me_idle_close_by_peer_total 40293
telemt_me_route_drop_no_conn_total 243086
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 631142
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2622
telemt_desync_full_logged_total 873
telemt_desync_suppressed_total 1749
telemt_desync_frames_bucket_total{bucket="1_2"} 547
telemt_desync_frames_bucket_total{bucket="3_10"} 988
telemt_desync_frames_bucket_total{bucket="gt_10"} 1087
telemt_pool_swap_total 169
telemt_me_writer_removed_unexpected_total 38276
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 37673
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 631040
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 17636039906 (16.42 GB)
telemt_user_octets_to_client{user="hello"} 303644806544 (282.79 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 187036.5 (51h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365712
telemt_connections_bad_total 2837
telemt_handshake_timeouts_total 3297
telemt_upstream_connect_attempt_total 155554
telemt_upstream_connect_success_total 154177
telemt_upstream_connect_fail_total 1377
telemt_upstream_connect_attempts_per_request{bucket="1"} 155554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39618
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2471
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1377
telemt_me_keepalive_timeout_total 5549
telemt_me_reconnect_attempts_total 193462
telemt_me_reconnect_success_total 41554
telemt_me_reader_eof_total 47379
telemt_me_idle_close_by_peer_total 47379
telemt_me_route_drop_no_conn_total 126458
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242177
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 46
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
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 46697
telemt_me_refill_failed_total 4739
telemt_me_writer_restored_same_endpoint_total 41536
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5143
telemt_user_connections_total{user="hello"} 345276
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 3520599335 (3.28 GB)
telemt_user_octets_to_client{user="hello"} 111511870403 (103.85 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 187000.2 (51h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422922
telemt_connections_bad_total 3307
telemt_handshake_timeouts_total 36387
telemt_upstream_connect_attempt_total 49939
telemt_upstream_connect_success_total 49930
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 49939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26910
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4102
telemt_me_reconnect_attempts_total 41836
telemt_me_reconnect_success_total 40517
telemt_me_reader_eof_total 43530
telemt_me_idle_close_by_peer_total 43530
telemt_me_route_drop_no_conn_total 154318
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 368081
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 138
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 75
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 174
telemt_me_writer_removed_unexpected_total 41005
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 40496
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 488
telemt_user_connections_total{user="hello"} 367846
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 15149548634 (14.11 GB)
telemt_user_octets_to_client{user="hello"} 161769899791 (150.66 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 186975.8 (51h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 535278
telemt_connections_bad_total 16770
telemt_handshake_timeouts_total 5279
telemt_upstream_connect_attempt_total 80184
telemt_upstream_connect_success_total 69487
telemt_upstream_connect_fail_total 10697
telemt_upstream_connect_attempts_per_request{bucket="1"} 80184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40434
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28671
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 373
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10697
telemt_me_keepalive_timeout_total 5731
telemt_me_reconnect_attempts_total 155781
telemt_me_reconnect_success_total 41142
telemt_me_reader_eof_total 46042
telemt_me_idle_close_by_peer_total 46034
telemt_me_route_drop_no_conn_total 194269
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 459142
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2083
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1470
telemt_desync_frames_bucket_total{bucket="1_2"} 486
telemt_desync_frames_bucket_total{bucket="3_10"} 790
telemt_desync_frames_bucket_total{bucket="gt_10"} 807
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 45191
telemt_me_refill_failed_total 3574
telemt_me_writer_restored_same_endpoint_total 41132
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4049
telemt_user_connections_total{user="hello"} 478008
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 10119327459 (9.42 GB)
telemt_user_octets_to_client{user="hello"} 195344548312 (181.93 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 137147.3 (38h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231651
telemt_connections_bad_total 36665
telemt_handshake_timeouts_total 2138
telemt_upstream_connect_attempt_total 48110
telemt_upstream_connect_success_total 47628
telemt_upstream_connect_fail_total 482
telemt_upstream_connect_attempts_per_request{bucket="1"} 48110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 482
telemt_me_keepalive_timeout_total 2940
telemt_me_reconnect_attempts_total 51788
telemt_me_reconnect_success_total 35900
telemt_me_reader_eof_total 38407
telemt_me_idle_close_by_peer_total 38407
telemt_me_route_drop_no_conn_total 70167
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181774
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 789
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 596
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 287
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 36733
telemt_me_refill_failed_total 492
telemt_me_writer_restored_same_endpoint_total 35882
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 833
telemt_user_connections_total{user="hello"} 186530
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 2737940273 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 86045074963 (80.14 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 186932.3 (51h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1088776
telemt_connections_bad_total 37452
telemt_handshake_timeouts_total 27105
telemt_upstream_connect_attempt_total 39028
telemt_upstream_connect_success_total 38824
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 39028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20393
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 4959
telemt_me_reconnect_attempts_total 34274
telemt_me_reconnect_success_total 29581
telemt_me_reader_eof_total 31718
telemt_me_idle_close_by_peer_total 31715
telemt_me_route_drop_no_conn_total 510707
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1009683
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 809
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 174
telemt_me_writer_removed_unexpected_total 30102
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 29574
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 521
telemt_user_connections_total{user="hello"} 982268
telemt_user_connections_current{user="hello"} 469
telemt_user_octets_from_client{user="hello"} 20971569396 (19.53 GB)
telemt_user_octets_to_client{user="hello"} 492477082028 (458.66 GB)
telemt_user_unique_ips_current{user="hello"} 186
telemt_user_unique_ips_recent_window{user="hello"} 63
```