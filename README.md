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

# Server Metrics 2026-03-19 22:50:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 19993.2 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 438676
telemt_connections_bad_total 27477
telemt_connections_current 758
telemt_connections_me_current 758
telemt_handshake_timeouts_total 6306
telemt_upstream_connect_attempt_total 3318
telemt_upstream_connect_success_total 3290
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 3318
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1665
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 2275
telemt_me_reconnect_success_total 2258
telemt_me_reader_eof_total 2398
telemt_me_idle_close_by_peer_total 2398
telemt_me_route_drop_no_conn_total 130352
telemt_me_route_drop_channel_closed_total 51
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 347324
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1857
telemt_desync_full_logged_total 655
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 602
telemt_desync_frames_bucket_total{bucket="gt_10"} 871
telemt_pool_swap_total 22
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 2307
telemt_me_writer_restored_same_endpoint_total 2245
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 347591
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 16726033552 (15.58 GB)
telemt_user_octets_to_client{user="hello"} 129419974736 (120.53 GB)
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 36448.7 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2817144
telemt_connections_bad_total 120540
telemt_connections_current 1551
telemt_connections_me_current 1551
telemt_handshake_timeouts_total 57052
telemt_upstream_connect_attempt_total 7365
telemt_upstream_connect_success_total 7251
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 7365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8418
telemt_me_reconnect_success_total 4186
telemt_me_reader_eof_total 4495
telemt_me_idle_close_by_peer_total 4495
telemt_me_route_drop_no_conn_total 1451732
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2406571
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10627
telemt_desync_full_logged_total 3488
telemt_desync_suppressed_total 7139
telemt_desync_frames_bucket_total{bucket="1_2"} 1988
telemt_desync_frames_bucket_total{bucket="3_10"} 4158
telemt_desync_frames_bucket_total{bucket="gt_10"} 4481
telemt_pool_swap_total 29
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 4359
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4131
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 2406449
telemt_user_connections_current{user="hello"} 1551
telemt_user_octets_from_client{user="hello"} 37797408454 (35.20 GB)
telemt_user_octets_to_client{user="hello"} 865421323566 (805.99 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 674
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 36426.7 (10h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2741528
telemt_connections_bad_total 462006
telemt_connections_current 1276
telemt_connections_me_current 1276
telemt_handshake_timeouts_total 35730
telemt_upstream_connect_attempt_total 5723
telemt_upstream_connect_success_total 5677
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 5723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4768
telemt_me_reconnect_success_total 3838
telemt_me_reader_eof_total 4001
telemt_me_idle_close_by_peer_total 4000
telemt_me_route_drop_no_conn_total 1873285
telemt_me_route_drop_channel_closed_total 169
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1911153
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7418
telemt_desync_full_logged_total 2247
telemt_desync_suppressed_total 5171
telemt_desync_frames_bucket_total{bucket="1_2"} 1824
telemt_desync_frames_bucket_total{bucket="3_10"} 2837
telemt_desync_frames_bucket_total{bucket="gt_10"} 2757
telemt_pool_swap_total 34
telemt_me_writer_close_signal_drop_total 63
telemt_me_writer_removed_unexpected_total 3868
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3837
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 1906955
telemt_user_connections_current{user="hello"} 1276
telemt_user_octets_from_client{user="hello"} 28770637476 (26.79 GB)
telemt_user_octets_to_client{user="hello"} 715557661080 (666.42 GB)
telemt_user_unique_ips_current{user="hello"} 515
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 36414.7 (10h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2393442
telemt_connections_bad_total 99934
telemt_connections_current 1123
telemt_connections_me_current 1123
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 29659
telemt_upstream_connect_attempt_total 36099
telemt_upstream_connect_success_total 34341
telemt_upstream_connect_fail_total 1758
telemt_upstream_connect_attempts_per_request{bucket="1"} 36099
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5745
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 459
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1758
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7061
telemt_me_reconnect_success_total 4423
telemt_me_reader_eof_total 4588
telemt_me_idle_close_by_peer_total 4587
telemt_me_route_drop_no_conn_total 1834384
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2032359
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8127
telemt_desync_full_logged_total 2562
telemt_desync_suppressed_total 5565
telemt_desync_frames_bucket_total{bucket="1_2"} 1990
telemt_desync_frames_bucket_total{bucket="3_10"} 2954
telemt_desync_frames_bucket_total{bucket="gt_10"} 3183
telemt_pool_swap_total 22
telemt_me_writer_close_signal_drop_total 349
telemt_me_writer_removed_unexpected_total 4951
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 4419
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 528
telemt_user_connections_total{user="hello"} 2059290
telemt_user_connections_current{user="hello"} 1123
telemt_user_octets_from_client{user="hello"} 33659606020 (31.35 GB)
telemt_user_octets_to_client{user="hello"} 541589166359 (504.39 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 454
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 90137.9 (25h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6070537
telemt_connections_bad_total 1036744
telemt_connections_current 1409
telemt_connections_me_current 1409
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 109820
telemt_upstream_connect_attempt_total 67374
telemt_upstream_connect_success_total 64865
telemt_upstream_connect_fail_total 2509
telemt_upstream_connect_attempts_per_request{bucket="1"} 67374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2509
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 76593
telemt_me_reconnect_success_total 11174
telemt_me_reader_eof_total 11800
telemt_me_idle_close_by_peer_total 11797
telemt_me_route_drop_no_conn_total 2760562
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4319136
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
telemt_desync_total 19018
telemt_desync_full_logged_total 5924
telemt_desync_suppressed_total 13094
telemt_desync_frames_bucket_total{bucket="1_2"} 3320
telemt_desync_frames_bucket_total{bucket="3_10"} 7809
telemt_desync_frames_bucket_total{bucket="gt_10"} 7889
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 11442
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 11150
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 4367191
telemt_user_connections_current{user="hello"} 1409
telemt_user_octets_from_client{user="hello"} 67685839079 (63.04 GB)
telemt_user_octets_to_client{user="hello"} 1698211134416 (1.54 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 584
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 36377.8 (10h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 643042
telemt_connections_bad_total 50851
telemt_connections_current 334
telemt_connections_me_current 334
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12462
telemt_upstream_connect_attempt_total 10245
telemt_upstream_connect_success_total 10004
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 10245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5589
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 591
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4933
telemt_me_reconnect_success_total 4847
telemt_me_reader_eof_total 5062
telemt_me_idle_close_by_peer_total 5060
telemt_me_route_drop_no_conn_total 451129
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 544906
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
telemt_desync_total 1362
telemt_desync_full_logged_total 508
telemt_desync_suppressed_total 854
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 558
telemt_desync_frames_bucket_total{bucket="gt_10"} 589
telemt_pool_swap_total 30
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 148
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4892
telemt_me_writer_restored_same_endpoint_total 4838
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 531894
telemt_user_connections_current{user="hello"} 334
telemt_user_octets_from_client{user="hello"} 6992836369 (6.51 GB)
telemt_user_octets_to_client{user="hello"} 128219497016 (119.41 GB)
telemt_user_msgs_from_client{user="hello"} 8558
telemt_user_msgs_to_client{user="hello"} 13690
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 36379.3 (10h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1902339
telemt_connections_bad_total 113448
telemt_connections_current 1304
telemt_connections_me_current 1304
telemt_handshake_timeouts_total 35494
telemt_upstream_connect_attempt_total 6199
telemt_upstream_connect_success_total 6153
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 6199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4343
telemt_me_reconnect_success_total 4308
telemt_me_reader_eof_total 4539
telemt_me_idle_close_by_peer_total 4539
telemt_me_route_drop_no_conn_total 708380
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1643358
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8800
telemt_desync_full_logged_total 2791
telemt_desync_suppressed_total 6009
telemt_desync_frames_bucket_total{bucket="1_2"} 1610
telemt_desync_frames_bucket_total{bucket="3_10"} 3083
telemt_desync_frames_bucket_total{bucket="gt_10"} 4107
telemt_pool_swap_total 35
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 4382
telemt_me_writer_restored_same_endpoint_total 4291
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1642495
telemt_user_connections_current{user="hello"} 1304
telemt_user_octets_from_client{user="hello"} 27966040496 (26.05 GB)
telemt_user_octets_to_client{user="hello"} 827437865764 (770.61 GB)
telemt_user_unique_ips_current{user="hello"} 525
telemt_user_unique_ips_recent_window{user="hello"} 116
```