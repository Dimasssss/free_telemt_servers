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

# Server Metrics 2026-03-13 20:46:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 133988.5 (37h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 563790
telemt_connections_bad_total 15563
telemt_handshake_timeouts_total 12648
telemt_upstream_connect_attempt_total 33989
telemt_upstream_connect_success_total 33817
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 33989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5065
telemt_me_reconnect_attempts_total 31400
telemt_me_reconnect_success_total 26747
telemt_me_reader_eof_total 28540
telemt_me_idle_close_by_peer_total 28539
telemt_me_route_drop_no_conn_total 186463
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 485827
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1549
telemt_desync_full_logged_total 526
telemt_desync_suppressed_total 1023
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 572
telemt_desync_frames_bucket_total{bucket="gt_10"} 641
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 27193
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 26731
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 446
telemt_user_connections_total{user="hello"} 485722
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 14046035778 (13.08 GB)
telemt_user_octets_to_client{user="hello"} 234479774740 (218.38 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 133881.6 (37h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285254
telemt_connections_bad_total 2102
telemt_handshake_timeouts_total 1896
telemt_upstream_connect_attempt_total 135478
telemt_upstream_connect_success_total 134495
telemt_upstream_connect_fail_total 983
telemt_upstream_connect_attempts_per_request{bucket="1"} 135478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 103131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2390
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 983
telemt_me_keepalive_timeout_total 3651
telemt_me_reconnect_attempts_total 142157
telemt_me_reconnect_success_total 26460
telemt_me_reader_eof_total 30807
telemt_me_idle_close_by_peer_total 30807
telemt_me_route_drop_no_conn_total 84030
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169416
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 34
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
telemt_me_writer_removed_unexpected_total 30321
telemt_me_refill_failed_total 3610
telemt_me_writer_restored_same_endpoint_total 26443
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3861
telemt_user_connections_total{user="hello"} 270570
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 2816255549 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 82184519328 (76.54 GB)
telemt_user_msgs_from_client{user="hello"} 1654532
telemt_user_msgs_to_client{user="hello"} 9194939
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 133845.3 (37h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331911
telemt_connections_bad_total 2650
telemt_handshake_timeouts_total 24772
telemt_upstream_connect_attempt_total 35540
telemt_upstream_connect_success_total 35535
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 35540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19073
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2821
telemt_me_reconnect_attempts_total 30060
telemt_me_reconnect_success_total 28820
telemt_me_reader_eof_total 30918
telemt_me_idle_close_by_peer_total 30918
telemt_me_route_drop_no_conn_total 118864
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 292824
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 29147
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 28800
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 292731
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 11914630084 (11.10 GB)
telemt_user_octets_to_client{user="hello"} 122313190396 (113.91 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 133820.8 (37h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 437774
telemt_connections_bad_total 15239
telemt_handshake_timeouts_total 4189
telemt_upstream_connect_attempt_total 63545
telemt_upstream_connect_success_total 53226
telemt_upstream_connect_fail_total 10319
telemt_upstream_connect_attempts_per_request{bucket="1"} 63545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19711
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 300
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10319
telemt_me_keepalive_timeout_total 4766
telemt_me_reconnect_attempts_total 123237
telemt_me_reconnect_success_total 27523
telemt_me_reader_eof_total 31290
telemt_me_idle_close_by_peer_total 31283
telemt_me_route_drop_no_conn_total 152016
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 368640
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1542
telemt_desync_full_logged_total 455
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 365
telemt_desync_frames_bucket_total{bucket="3_10"} 585
telemt_desync_frames_bucket_total{bucket="gt_10"} 592
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 30861
telemt_me_refill_failed_total 2985
telemt_me_writer_restored_same_endpoint_total 27513
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3338
telemt_user_connections_total{user="hello"} 387497
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 8731810047 (8.13 GB)
telemt_user_octets_to_client{user="hello"} 142794646088 (132.99 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 83992.4 (23h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143653
telemt_connections_bad_total 19891
telemt_handshake_timeouts_total 1520
telemt_upstream_connect_attempt_total 31779
telemt_upstream_connect_success_total 31473
telemt_upstream_connect_fail_total 306
telemt_upstream_connect_attempts_per_request{bucket="1"} 31779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15148
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 306
telemt_me_keepalive_timeout_total 1283
telemt_me_reconnect_attempts_total 35763
telemt_me_reconnect_success_total 22369
telemt_me_reader_eof_total 23966
telemt_me_idle_close_by_peer_total 23966
telemt_me_route_drop_no_conn_total 44431
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112812
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 607
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 22998
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 22351
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 629
telemt_user_connections_total{user="hello"} 117706
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 1370405389 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 53476595263 (49.80 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 133777.0 (37h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 816915
telemt_connections_bad_total 25229
telemt_handshake_timeouts_total 25040
telemt_upstream_connect_attempt_total 27588
telemt_upstream_connect_success_total 27442
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 27588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14582
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 3095
telemt_me_reconnect_attempts_total 25457
telemt_me_reconnect_success_total 20808
telemt_me_reader_eof_total 22314
telemt_me_idle_close_by_peer_total 22311
telemt_me_route_drop_no_conn_total 389280
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 765885
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 21230
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 20801
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 422
telemt_user_connections_total{user="hello"} 738747
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 12928071640 (12.04 GB)
telemt_user_octets_to_client{user="hello"} 367034826556 (341.83 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 45
```