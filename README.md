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

# Server Metrics 2026-03-12 17:09:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 34553.5 (9h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180898
telemt_connections_bad_total 2388
telemt_handshake_timeouts_total 4908
telemt_upstream_connect_attempt_total 8695
telemt_upstream_connect_success_total 8663
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 8695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4808
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 363
telemt_me_reconnect_attempts_total 8011
telemt_me_reconnect_success_total 6872
telemt_me_reader_eof_total 7239
telemt_me_idle_close_by_peer_total 7238
telemt_me_route_drop_no_conn_total 52743
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153942
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 624
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 391
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6979
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 6856
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 153902
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 2662857036 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 63066078344 (58.73 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 34446.2 (9h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76126
telemt_connections_bad_total 467
telemt_handshake_timeouts_total 637
telemt_upstream_connect_attempt_total 10824
telemt_upstream_connect_success_total 10595
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 10824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6271
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_timeout_total 301
telemt_me_reconnect_attempts_total 34660
telemt_me_reconnect_success_total 8836
telemt_me_reader_eof_total 9811
telemt_me_idle_close_by_peer_total 9811
telemt_me_route_drop_no_conn_total 33563
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72291
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 9710
telemt_me_refill_failed_total 806
telemt_me_writer_restored_same_endpoint_total 8821
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 874
telemt_user_connections_total{user="hello"} 72276
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 796528468 (759.63 MB)
telemt_user_octets_to_client{user="hello"} 20082806004 (18.70 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 34409.7 (9h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102613
telemt_connections_bad_total 1495
telemt_handshake_timeouts_total 2059
telemt_upstream_connect_attempt_total 9543
telemt_upstream_connect_success_total 9543
telemt_upstream_connect_attempts_per_request{bucket="1"} 9543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4903
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 203
telemt_me_reconnect_attempts_total 7797
telemt_me_reconnect_success_total 7727
telemt_me_reader_eof_total 8187
telemt_me_idle_close_by_peer_total 8187
telemt_me_route_drop_no_conn_total 38092
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94860
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 7798
telemt_me_writer_restored_same_endpoint_total 7707
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 94834
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 2286566556 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 49288561176 (45.90 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 34385.6 (9h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141047
telemt_connections_bad_total 13066
telemt_handshake_timeouts_total 1073
telemt_upstream_connect_attempt_total 7458
telemt_upstream_connect_success_total 7221
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 7458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3830
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_keepalive_timeout_total 357
telemt_me_reconnect_attempts_total 33536
telemt_me_reconnect_success_total 5447
telemt_me_reader_eof_total 6458
telemt_me_idle_close_by_peer_total 6458
telemt_me_route_drop_no_conn_total 50616
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119768
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 407
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 287
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 6386
telemt_me_refill_failed_total 876
telemt_me_writer_restored_same_endpoint_total 5439
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 939
telemt_user_connections_total{user="hello"} 119650
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 2180731744 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 51201386400 (47.69 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 34354.8 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84759
telemt_connections_bad_total 9057
telemt_handshake_timeouts_total 1134
telemt_upstream_connect_attempt_total 43710
telemt_upstream_connect_success_total 43283
telemt_upstream_connect_fail_total 427
telemt_upstream_connect_attempts_per_request{bucket="1"} 43710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 427
telemt_me_keepalive_timeout_total 137
telemt_me_reconnect_attempts_total 46952
telemt_me_reconnect_success_total 3703
telemt_me_reader_eof_total 5049
telemt_me_idle_close_by_peer_total 5049
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 13087
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34685
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 5077
telemt_me_refill_failed_total 1354
telemt_me_writer_restored_same_endpoint_total 3686
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1374
telemt_user_connections_total{user="hello"} 72493
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 673278313 (642.09 MB)
telemt_user_octets_to_client{user="hello"} 22083827708 (20.57 GB)
telemt_user_msgs_from_client{user="hello"} 607569
telemt_user_msgs_to_client{user="hello"} 2270284
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 34342.8 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218234
telemt_connections_bad_total 974
telemt_handshake_timeouts_total 1757
telemt_upstream_connect_attempt_total 7422
telemt_upstream_connect_success_total 7385
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 7422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3919
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 421
telemt_me_reconnect_attempts_total 6843
telemt_me_reconnect_success_total 5613
telemt_me_reader_eof_total 5917
telemt_me_idle_close_by_peer_total 5916
telemt_me_route_drop_no_conn_total 99362
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218443
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 253
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5726
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 5606
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 208378
telemt_user_connections_current{user="hello"} 464
telemt_user_octets_from_client{user="hello"} 3816401528 (3.55 GB)
telemt_user_octets_to_client{user="hello"} 95888359968 (89.30 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 68
```