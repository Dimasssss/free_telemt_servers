# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-19 23:16:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 21522.5 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 456209
telemt_connections_bad_total 28832
telemt_connections_current 764
telemt_connections_me_current 764
telemt_handshake_timeouts_total 7021
telemt_upstream_connect_attempt_total 3558
telemt_upstream_connect_success_total 3528
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 3558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1797
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 2470
telemt_me_reconnect_success_total 2452
telemt_me_reader_eof_total 2600
telemt_me_idle_close_by_peer_total 2600
telemt_me_route_drop_no_conn_total 135334
telemt_me_route_drop_channel_closed_total 51
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361747
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1937
telemt_desync_full_logged_total 678
telemt_desync_suppressed_total 1259
telemt_desync_frames_bucket_total{bucket="1_2"} 404
telemt_desync_frames_bucket_total{bucket="3_10"} 632
telemt_desync_frames_bucket_total{bucket="gt_10"} 901
telemt_pool_swap_total 23
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2503
telemt_me_writer_restored_same_endpoint_total 2439
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 362020
telemt_user_connections_current{user="hello"} 764
telemt_user_octets_from_client{user="hello"} 20744688284 (19.32 GB)
telemt_user_octets_to_client{user="hello"} 133639266264 (124.46 GB)
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 37977.8 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2853868
telemt_connections_bad_total 122716
telemt_connections_current 1511
telemt_connections_me_current 1511
telemt_handshake_timeouts_total 58389
telemt_upstream_connect_attempt_total 7640
telemt_upstream_connect_success_total 7517
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 7640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2942
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8600
telemt_me_reconnect_success_total 4365
telemt_me_reader_eof_total 4685
telemt_me_idle_close_by_peer_total 4685
telemt_me_route_drop_no_conn_total 1462555
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2438739
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10715
telemt_desync_full_logged_total 3529
telemt_desync_suppressed_total 7186
telemt_desync_frames_bucket_total{bucket="1_2"} 2007
telemt_desync_frames_bucket_total{bucket="3_10"} 4199
telemt_desync_frames_bucket_total{bucket="gt_10"} 4509
telemt_pool_swap_total 31
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 4544
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4310
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 2438568
telemt_user_connections_current{user="hello"} 1511
telemt_user_octets_from_client{user="hello"} 38173947286 (35.55 GB)
telemt_user_octets_to_client{user="hello"} 880779957106 (820.29 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 665
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 37956.2 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2774810
telemt_connections_bad_total 463653
telemt_connections_current 1158
telemt_connections_me_current 1158
telemt_handshake_timeouts_total 36607
telemt_upstream_connect_attempt_total 6003
telemt_upstream_connect_success_total 5955
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 6003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2883
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4960
telemt_me_reconnect_success_total 4030
telemt_me_reader_eof_total 4204
telemt_me_idle_close_by_peer_total 4203
telemt_me_route_drop_no_conn_total 1881829
telemt_me_route_drop_channel_closed_total 169
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1932550
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7504
telemt_desync_full_logged_total 2265
telemt_desync_suppressed_total 5239
telemt_desync_frames_bucket_total{bucket="1_2"} 1844
telemt_desync_frames_bucket_total{bucket="3_10"} 2858
telemt_desync_frames_bucket_total{bucket="gt_10"} 2802
telemt_pool_swap_total 36
telemt_me_writer_close_signal_drop_total 64
telemt_me_writer_removed_unexpected_total 4064
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4029
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 1928344
telemt_user_connections_current{user="hello"} 1158
telemt_user_octets_from_client{user="hello"} 29004333944 (27.01 GB)
telemt_user_octets_to_client{user="hello"} 730525271660 (680.35 GB)
telemt_user_unique_ips_current{user="hello"} 501
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 37943.9 (10h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2422047
telemt_connections_bad_total 100190
telemt_connections_current 1065
telemt_connections_me_current 1065
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 29808
telemt_upstream_connect_attempt_total 52957
telemt_upstream_connect_success_total 48809
telemt_upstream_connect_fail_total 4148
telemt_upstream_connect_attempts_per_request{bucket="1"} 52957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 513
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4148
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7311
telemt_me_reconnect_success_total 4567
telemt_me_reader_eof_total 4728
telemt_me_idle_close_by_peer_total 4727
telemt_me_route_drop_no_conn_total 1837847
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2042240
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8141
telemt_desync_full_logged_total 2567
telemt_desync_suppressed_total 5574
telemt_desync_frames_bucket_total{bucket="1_2"} 1993
telemt_desync_frames_bucket_total{bucket="3_10"} 2961
telemt_desync_frames_bucket_total{bucket="gt_10"} 3187
telemt_pool_swap_total 24
telemt_me_writer_close_signal_drop_total 403
telemt_me_writer_removed_unexpected_total 5128
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 4563
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 2083396
telemt_user_connections_current{user="hello"} 1065
telemt_user_octets_from_client{user="hello"} 34041010147 (31.70 GB)
telemt_user_octets_to_client{user="hello"} 556613452999 (518.39 GB)
telemt_user_msgs_from_client{user="hello"} 239211
telemt_user_msgs_to_client{user="hello"} 1739348
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 91667.4 (25h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6128998
telemt_connections_bad_total 1037063
telemt_connections_current 1171
telemt_connections_direct_current 1171
telemt_relay_adaptive_promotions_total 24
telemt_relay_adaptive_demotions_total 3387
telemt_relay_adaptive_hard_promotions_total 22
telemt_handshake_timeouts_total 110309
telemt_upstream_connect_attempt_total 113043
telemt_upstream_connect_success_total 81719
telemt_upstream_connect_fail_total 31323
telemt_upstream_connect_attempts_per_request{bucket="1"} 113042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31323
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 77182
telemt_me_reconnect_success_total 11644
telemt_me_reader_eof_total 12407
telemt_me_idle_close_by_peer_total 12396
telemt_me_route_drop_no_conn_total 2763369
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4329828
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19068
telemt_desync_full_logged_total 5962
telemt_desync_suppressed_total 13106
telemt_desync_frames_bucket_total{bucket="1_2"} 3332
telemt_desync_frames_bucket_total{bucket="3_10"} 7824
telemt_desync_frames_bucket_total{bucket="gt_10"} 7912
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 11932
telemt_me_refill_failed_total 2043
telemt_me_writer_restored_same_endpoint_total 11619
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 4394230
telemt_user_connections_current{user="hello"} 1171
telemt_user_octets_from_client{user="hello"} 67860362791 (63.20 GB)
telemt_user_octets_to_client{user="hello"} 1704435073244 (1.55 TB)
telemt_user_msgs_from_client{user="hello"} 671975
telemt_user_msgs_to_client{user="hello"} 2624457
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 37907.2 (10h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 662247
telemt_connections_bad_total 61809
telemt_connections_current 313
telemt_connections_me_current 313
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12810
telemt_upstream_connect_attempt_total 11243
telemt_upstream_connect_success_total 10944
telemt_upstream_connect_fail_total 299
telemt_upstream_connect_attempts_per_request{bucket="1"} 11243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5849
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 626
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 299
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 5186
telemt_me_reconnect_success_total 5087
telemt_me_reader_eof_total 5299
telemt_me_idle_close_by_peer_total 5297
telemt_me_route_drop_no_conn_total 453727
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 551404
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1380
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 866
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 566
telemt_desync_frames_bucket_total{bucket="gt_10"} 596
telemt_pool_swap_total 32
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 149
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 5130
telemt_me_writer_restored_same_endpoint_total 5078
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 539028
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 7048290998 (6.56 GB)
telemt_user_octets_to_client{user="hello"} 130023415766 (121.09 GB)
telemt_user_msgs_from_client{user="hello"} 10105
telemt_user_msgs_to_client{user="hello"} 15806
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 37908.5 (10h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1924438
telemt_connections_bad_total 116595
telemt_connections_current 1198
telemt_connections_me_current 1198
telemt_handshake_timeouts_total 35720
telemt_upstream_connect_attempt_total 6496
telemt_upstream_connect_success_total 6445
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 6496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4549
telemt_me_reconnect_success_total 4512
telemt_me_reader_eof_total 4754
telemt_me_idle_close_by_peer_total 4754
telemt_me_route_drop_no_conn_total 715159
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1660122
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8835
telemt_desync_full_logged_total 2813
telemt_desync_suppressed_total 6022
telemt_desync_frames_bucket_total{bucket="1_2"} 1618
telemt_desync_frames_bucket_total{bucket="3_10"} 3098
telemt_desync_frames_bucket_total{bucket="gt_10"} 4119
telemt_pool_swap_total 37
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 4588
telemt_me_writer_restored_same_endpoint_total 4495
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 1659259
telemt_user_connections_current{user="hello"} 1198
telemt_user_octets_from_client{user="hello"} 28166239820 (26.23 GB)
telemt_user_octets_to_client{user="hello"} 838741567192 (781.14 GB)
telemt_user_unique_ips_current{user="hello"} 493
telemt_user_unique_ips_recent_window{user="hello"} 94
```