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

# Server Metrics 2026-03-16 13:21:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 140807.1 (39h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 800971
telemt_connections_bad_total 54283
telemt_handshake_timeouts_total 26871
telemt_upstream_connect_attempt_total 32571
telemt_upstream_connect_success_total 32413
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 32571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 39638
telemt_me_reconnect_success_total 25401
telemt_me_reader_eof_total 27386
telemt_me_idle_close_by_peer_total 27386
telemt_me_route_drop_no_conn_total 619781
telemt_me_route_drop_channel_closed_total 99
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 733267
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3485
telemt_desync_full_logged_total 1312
telemt_desync_suppressed_total 2173
telemt_desync_frames_bucket_total{bucket="1_2"} 743
telemt_desync_frames_bucket_total{bucket="3_10"} 1455
telemt_desync_frames_bucket_total{bucket="gt_10"} 1287
telemt_pool_swap_total 126
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26126
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 25366
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 725
telemt_user_connections_total{user="hello"} 669736
telemt_user_connections_current{user="hello"} 717
telemt_user_octets_from_client{user="hello"} 13882793040 (12.93 GB)
telemt_user_octets_to_client{user="hello"} 381286175816 (355.10 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 140814.9 (39h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 364721
telemt_connections_bad_total 30798
telemt_handshake_timeouts_total 21673
telemt_upstream_connect_attempt_total 37560
telemt_upstream_connect_success_total 37453
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 37560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20388
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 898
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1697
telemt_me_reconnect_attempts_total 46069
telemt_me_reconnect_success_total 29809
telemt_me_reader_eof_total 32060
telemt_me_idle_close_by_peer_total 32059
telemt_me_route_drop_no_conn_total 158705
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299834
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 256
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 173
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 30745
telemt_me_refill_failed_total 498
telemt_me_writer_restored_same_endpoint_total 29793
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 936
telemt_user_connections_total{user="hello"} 299499
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 5870629581 (5.47 GB)
telemt_user_octets_to_client{user="hello"} 143569252156 (133.71 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 140807.3 (39h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322282
telemt_connections_bad_total 8726
telemt_handshake_timeouts_total 9060
telemt_upstream_connect_attempt_total 38816
telemt_upstream_connect_success_total 38806
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 38816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21960
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 88
telemt_me_reconnect_attempts_total 39165
telemt_me_reconnect_success_total 31711
telemt_me_reader_eof_total 34034
telemt_me_idle_close_by_peer_total 34033
telemt_me_route_drop_no_conn_total 108817
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262751
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 32269
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 31703
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 558
telemt_user_connections_total{user="hello"} 262340
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 19227936061 (17.91 GB)
telemt_user_octets_to_client{user="hello"} 133501180824 (124.33 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 140806.6 (39h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 497100
telemt_connections_bad_total 5609
telemt_handshake_timeouts_total 6671
telemt_upstream_connect_attempt_total 32707
telemt_upstream_connect_success_total 32657
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 32707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15724
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16735
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 181
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 128
telemt_me_reconnect_attempts_total 33066
telemt_me_reconnect_success_total 25620
telemt_me_reader_eof_total 27469
telemt_me_idle_close_by_peer_total 27468
telemt_me_route_drop_no_conn_total 165200
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 453509
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1635
telemt_desync_full_logged_total 542
telemt_desync_suppressed_total 1093
telemt_desync_frames_bucket_total{bucket="1_2"} 330
telemt_desync_frames_bucket_total{bucket="3_10"} 704
telemt_desync_frames_bucket_total{bucket="gt_10"} 601
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 26198
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 25609
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 578
telemt_user_connections_total{user="hello"} 453314
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 6898676706 (6.42 GB)
telemt_user_octets_to_client{user="hello"} 168994312040 (157.39 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 115878.1 (32h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306054
telemt_connections_bad_total 56739
telemt_handshake_timeouts_total 6290
telemt_upstream_connect_attempt_total 32953
telemt_upstream_connect_success_total 32773
telemt_upstream_connect_fail_total 180
telemt_upstream_connect_attempts_per_request{bucket="1"} 32953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18231
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 180
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 122455
telemt_me_reconnect_success_total 26833
telemt_me_reader_eof_total 28477
telemt_me_idle_close_by_peer_total 28477
telemt_me_route_drop_no_conn_total 90482
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 233737
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 722
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 546
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 293
telemt_desync_frames_bucket_total{bucket="gt_10"} 321
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 27111
telemt_me_refill_failed_total 3067
telemt_me_writer_restored_same_endpoint_total 26729
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 233339
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 3050157741 (2.84 GB)
telemt_user_octets_to_client{user="hello"} 107985354227 (100.57 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 140807.0 (39h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1030800
telemt_connections_bad_total 78530
telemt_handshake_timeouts_total 13113
telemt_upstream_connect_attempt_total 29911
telemt_upstream_connect_success_total 29754
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 29911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 200
telemt_me_reconnect_attempts_total 26356
telemt_me_reconnect_success_total 22702
telemt_me_reader_eof_total 24238
telemt_me_idle_close_by_peer_total 24237
telemt_me_route_drop_no_conn_total 729311
telemt_me_route_drop_channel_closed_total 142
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 999319
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 756
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 521
telemt_desync_frames_bucket_total{bucket="1_2"} 189
telemt_desync_frames_bucket_total{bucket="3_10"} 276
telemt_desync_frames_bucket_total{bucket="gt_10"} 291
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 23091
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 22675
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 389
telemt_user_connections_total{user="hello"} 857895
telemt_user_connections_current{user="hello"} 682
telemt_user_octets_from_client{user="hello"} 18187876760 (16.94 GB)
telemt_user_octets_to_client{user="hello"} 488772834748 (455.21 GB)
telemt_user_unique_ips_current{user="hello"} 255
telemt_user_unique_ips_recent_window{user="hello"} 89
```