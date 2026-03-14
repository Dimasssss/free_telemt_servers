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

# Server Metrics 2026-03-14 04:35:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 162102.1 (45h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 628310
telemt_connections_bad_total 31704
telemt_handshake_timeouts_total 12949
telemt_upstream_connect_attempt_total 41451
telemt_upstream_connect_success_total 41241
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 41451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5551
telemt_me_reconnect_attempts_total 37439
telemt_me_reconnect_success_total 32755
telemt_me_reader_eof_total 35005
telemt_me_idle_close_by_peer_total 35004
telemt_me_route_drop_no_conn_total 204248
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 531783
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1831
telemt_desync_full_logged_total 620
telemt_desync_suppressed_total 1211
telemt_desync_frames_bucket_total{bucket="1_2"} 391
telemt_desync_frames_bucket_total{bucket="3_10"} 676
telemt_desync_frames_bucket_total{bucket="gt_10"} 764
telemt_pool_swap_total 149
telemt_me_writer_removed_unexpected_total 33258
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 32735
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 503
telemt_user_connections_total{user="hello"} 531668
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 15761469934 (14.68 GB)
telemt_user_octets_to_client{user="hello"} 258131038412 (240.40 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 161995.1 (44h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 317748
telemt_connections_bad_total 2270
telemt_handshake_timeouts_total 2330
telemt_upstream_connect_attempt_total 147087
telemt_upstream_connect_success_total 145898
telemt_upstream_connect_fail_total 1189
telemt_upstream_connect_attempts_per_request{bucket="1"} 147087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1189
telemt_me_keepalive_timeout_total 3869
telemt_me_reconnect_attempts_total 171341
telemt_me_reconnect_success_total 34532
telemt_me_reader_eof_total 39705
telemt_me_idle_close_by_peer_total 39705
telemt_me_route_drop_no_conn_total 100833
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 197805
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 41
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
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 39136
telemt_me_refill_failed_total 4269
telemt_me_writer_restored_same_endpoint_total 34515
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4604
telemt_user_connections_total{user="hello"} 300916
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 3137807359 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 97096991791 (90.43 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 161958.7 (44h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 370128
telemt_connections_bad_total 2933
telemt_handshake_timeouts_total 34817
telemt_upstream_connect_attempt_total 42912
telemt_upstream_connect_success_total 42903
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 42912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23232
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3394
telemt_me_reconnect_attempts_total 36086
telemt_me_reconnect_success_total 34804
telemt_me_reader_eof_total 37409
telemt_me_idle_close_by_peer_total 37409
telemt_me_route_drop_no_conn_total 132742
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 319572
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
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
telemt_pool_swap_total 152
telemt_me_writer_removed_unexpected_total 35229
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 34783
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 319356
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 12704023560 (11.83 GB)
telemt_user_octets_to_client{user="hello"} 128181938520 (119.38 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 161934.3 (44h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 471808
telemt_connections_bad_total 15568
telemt_handshake_timeouts_total 4410
telemt_upstream_connect_attempt_total 72675
telemt_upstream_connect_success_total 62156
telemt_upstream_connect_fail_total 10519
telemt_upstream_connect_attempts_per_request{bucket="1"} 72675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24773
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 333
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10519
telemt_me_keepalive_timeout_total 5286
telemt_me_reconnect_attempts_total 141117
telemt_me_reconnect_success_total 35070
telemt_me_reader_eof_total 39463
telemt_me_idle_close_by_peer_total 39455
telemt_me_route_drop_no_conn_total 168990
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 400472
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1712
telemt_desync_full_logged_total 504
telemt_desync_suppressed_total 1208
telemt_desync_frames_bucket_total{bucket="1_2"} 401
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 664
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 38787
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 35060
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3717
telemt_user_connections_total{user="hello"} 419322
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 9202148919 (8.57 GB)
telemt_user_octets_to_client{user="hello"} 163751409284 (152.51 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 112105.7 (31h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184490
telemt_connections_bad_total 26646
telemt_handshake_timeouts_total 1641
telemt_upstream_connect_attempt_total 40376
telemt_upstream_connect_success_total 40001
telemt_upstream_connect_fail_total 375
telemt_upstream_connect_attempts_per_request{bucket="1"} 40376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 375
telemt_me_keepalive_timeout_total 2381
telemt_me_reconnect_attempts_total 42948
telemt_me_reconnect_success_total 29526
telemt_me_reader_eof_total 31595
telemt_me_idle_close_by_peer_total 31595
telemt_me_route_drop_no_conn_total 54766
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146244
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 30210
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 29508
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 684
telemt_user_connections_total{user="hello"} 150997
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 2245114513 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 68920027307 (64.19 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 161890.2 (44h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 920378
telemt_connections_bad_total 28224
telemt_handshake_timeouts_total 25594
telemt_upstream_connect_attempt_total 33638
telemt_upstream_connect_success_total 33457
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 33638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17740
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 4581
telemt_me_reconnect_attempts_total 30131
telemt_me_reconnect_success_total 25460
telemt_me_reader_eof_total 27326
telemt_me_idle_close_by_peer_total 27323
telemt_me_route_drop_no_conn_total 437845
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 859328
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 152
telemt_me_writer_removed_unexpected_total 25931
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 25453
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 831992
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 14512310952 (13.52 GB)
telemt_user_octets_to_client{user="hello"} 421109623796 (392.19 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 54
```