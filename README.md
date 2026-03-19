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

# Server Metrics 2026-03-19 18:58:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 6039.2 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195486
telemt_connections_bad_total 7194
telemt_connections_current 1444
telemt_connections_me_current 1444
telemt_handshake_timeouts_total 2082
telemt_upstream_connect_attempt_total 889
telemt_upstream_connect_success_total 876
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 439
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 551
telemt_me_reconnect_success_total 548
telemt_me_reader_eof_total 563
telemt_me_idle_close_by_peer_total 563
telemt_me_route_drop_no_conn_total 59812
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153885
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 690
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 465
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 330
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 565
telemt_me_writer_restored_same_endpoint_total 535
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 154099
telemt_user_connections_current{user="hello"} 1444
telemt_user_octets_from_client{user="hello"} 2408770416 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 51670940620 (48.12 GB)
telemt_user_unique_ips_current{user="hello"} 440
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 22494.7 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2183176
telemt_connections_bad_total 101153
telemt_connections_current 3686
telemt_connections_me_current 3686
telemt_handshake_timeouts_total 41246
telemt_upstream_connect_attempt_total 4998
telemt_upstream_connect_success_total 4932
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 4998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1663
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6790
telemt_me_reconnect_success_total 2565
telemt_me_reader_eof_total 2765
telemt_me_idle_close_by_peer_total 2765
telemt_me_route_drop_no_conn_total 1219276
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1830749
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7485
telemt_desync_full_logged_total 2389
telemt_desync_suppressed_total 5096
telemt_desync_frames_bucket_total{bucket="1_2"} 1407
telemt_desync_frames_bucket_total{bucket="3_10"} 2957
telemt_desync_frames_bucket_total{bucket="gt_10"} 3121
telemt_pool_swap_total 15
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2712
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2510
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 1830694
telemt_user_connections_current{user="hello"} 3686
telemt_user_octets_from_client{user="hello"} 26714393786 (24.88 GB)
telemt_user_octets_to_client{user="hello"} 606299110194 (564.66 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1271
telemt_user_unique_ips_recent_window{user="hello"} 480
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 22472.7 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1988039
telemt_connections_bad_total 236587
telemt_connections_current 2741
telemt_connections_me_current 2741
telemt_handshake_timeouts_total 23061
telemt_upstream_connect_attempt_total 3497
telemt_upstream_connect_success_total 3472
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1621
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3251
telemt_me_reconnect_success_total 2333
telemt_me_reader_eof_total 2388
telemt_me_idle_close_by_peer_total 2387
telemt_me_route_drop_no_conn_total 1714481
telemt_me_route_drop_channel_closed_total 147
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1513171
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5177
telemt_desync_full_logged_total 1544
telemt_desync_suppressed_total 3633
telemt_desync_frames_bucket_total{bucket="1_2"} 1323
telemt_desync_frames_bucket_total{bucket="3_10"} 1947
telemt_desync_frames_bucket_total{bucket="gt_10"} 1907
telemt_pool_swap_total 18
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 2331
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2332
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1509532
telemt_user_connections_current{user="hello"} 2741
telemt_user_octets_from_client{user="hello"} 20036306080 (18.66 GB)
telemt_user_octets_to_client{user="hello"} 494918607428 (460.93 GB)
telemt_user_unique_ips_current{user="hello"} 926
telemt_user_unique_ips_recent_window{user="hello"} 337
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 22460.5 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1860328
telemt_connections_bad_total 62010
telemt_connections_current 2712
telemt_connections_me_current 2712
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 24575
telemt_upstream_connect_attempt_total 25536
telemt_upstream_connect_success_total 24341
telemt_upstream_connect_fail_total 1195
telemt_upstream_connect_attempts_per_request{bucket="1"} 25536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4125
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1195
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5160
telemt_me_reconnect_success_total 2776
telemt_me_reader_eof_total 2872
telemt_me_idle_close_by_peer_total 2871
telemt_me_route_drop_no_conn_total 1611814
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1605381
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6353
telemt_desync_full_logged_total 1971
telemt_desync_suppressed_total 4382
telemt_desync_frames_bucket_total{bucket="1_2"} 1638
telemt_desync_frames_bucket_total{bucket="3_10"} 2336
telemt_desync_frames_bucket_total{bucket="gt_10"} 2379
telemt_pool_swap_total 9
telemt_me_writer_close_signal_drop_total 200
telemt_me_writer_removed_unexpected_total 3191
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2772
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 415
telemt_user_connections_total{user="hello"} 1624714
telemt_user_connections_current{user="hello"} 2712
telemt_user_octets_from_client{user="hello"} 27837137253 (25.93 GB)
telemt_user_octets_to_client{user="hello"} 361986029105 (337.13 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 938
telemt_user_unique_ips_recent_window{user="hello"} 377
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 76183.7 (21h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5552586
telemt_connections_bad_total 1008904
telemt_connections_current 3127
telemt_connections_me_current 3127
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 101182
telemt_upstream_connect_attempt_total 65111
telemt_upstream_connect_success_total 62617
telemt_upstream_connect_fail_total 2494
telemt_upstream_connect_attempts_per_request{bucket="1"} 65111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8509
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1050
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2494
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 75035
telemt_me_reconnect_success_total 9625
telemt_me_reader_eof_total 10146
telemt_me_idle_close_by_peer_total 10143
telemt_me_route_drop_no_conn_total 2547713
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3866636
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
telemt_desync_total 16999
telemt_desync_full_logged_total 5216
telemt_desync_suppressed_total 11783
telemt_desync_frames_bucket_total{bucket="1_2"} 2821
telemt_desync_frames_bucket_total{bucket="3_10"} 7061
telemt_desync_frames_bucket_total{bucket="gt_10"} 7117
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 9872
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9601
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 3914761
telemt_user_connections_current{user="hello"} 3127
telemt_user_octets_from_client{user="hello"} 61330812687 (57.12 GB)
telemt_user_octets_to_client{user="hello"} 1443882667404 (1.31 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1085
telemt_user_unique_ips_recent_window{user="hello"} 425
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 22424.4 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515361
telemt_connections_bad_total 36576
telemt_connections_current 596
telemt_connections_me_current 596
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 10451
telemt_upstream_connect_attempt_total 7301
telemt_upstream_connect_success_total 7104
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 7301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4096
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 549
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 424
telemt_me_reconnect_attempts_total 3031
telemt_me_reconnect_success_total 2974
telemt_me_reader_eof_total 3057
telemt_me_idle_close_by_peer_total 3056
telemt_me_route_drop_no_conn_total 362880
telemt_me_route_drop_channel_closed_total 127
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408226
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
telemt_desync_total 1089
telemt_desync_full_logged_total 346
telemt_desync_suppressed_total 743
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 443
telemt_desync_frames_bucket_total{bucket="gt_10"} 471
telemt_pool_swap_total 14
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 133
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 2996
telemt_me_writer_restored_same_endpoint_total 2965
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 426872
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 4862776908 (4.53 GB)
telemt_user_octets_to_client{user="hello"} 89522808986 (83.37 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 22425.3 (6h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1453900
telemt_connections_bad_total 89128
telemt_connections_current 2923
telemt_connections_me_current 2923
telemt_handshake_timeouts_total 25063
telemt_upstream_connect_attempt_total 3668
telemt_upstream_connect_success_total 3641
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 3668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 2523
telemt_me_reconnect_success_total 2496
telemt_me_reader_eof_total 2617
telemt_me_idle_close_by_peer_total 2617
telemt_me_route_drop_no_conn_total 557295
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1260329
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6671
telemt_desync_full_logged_total 2059
telemt_desync_suppressed_total 4612
telemt_desync_frames_bucket_total{bucket="1_2"} 1263
telemt_desync_frames_bucket_total{bucket="3_10"} 2333
telemt_desync_frames_bucket_total{bucket="gt_10"} 3075
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 33
telemt_me_writer_removed_unexpected_total 2547
telemt_me_writer_restored_same_endpoint_total 2479
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 1259579
telemt_user_connections_current{user="hello"} 2923
telemt_user_octets_from_client{user="hello"} 20072177492 (18.69 GB)
telemt_user_octets_to_client{user="hello"} 561960603032 (523.37 GB)
telemt_user_unique_ips_current{user="hello"} 951
telemt_user_unique_ips_recent_window{user="hello"} 333
```