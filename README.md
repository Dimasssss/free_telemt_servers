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

# Server Metrics 2026-03-20 00:37:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 26424.1 (7h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 516159
telemt_connections_bad_total 33331
telemt_connections_current 832
telemt_connections_me_current 832
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 7543
telemt_upstream_connect_attempt_total 5710
telemt_upstream_connect_success_total 5634
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 5710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2293
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3205
telemt_me_reconnect_success_total 3175
telemt_me_reader_eof_total 3341
telemt_me_idle_close_by_peer_total 3340
telemt_me_route_drop_no_conn_total 151283
telemt_me_route_drop_channel_closed_total 56
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 410409
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2024
telemt_desync_full_logged_total 725
telemt_desync_suppressed_total 1299
telemt_desync_frames_bucket_total{bucket="1_2"} 415
telemt_desync_frames_bucket_total{bucket="3_10"} 680
telemt_desync_frames_bucket_total{bucket="gt_10"} 929
telemt_pool_swap_total 29
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3192
telemt_me_writer_restored_same_endpoint_total 3162
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 411840
telemt_user_connections_current{user="hello"} 832
telemt_user_octets_from_client{user="hello"} 29324085236 (27.31 GB)
telemt_user_octets_to_client{user="hello"} 149046736741 (138.81 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 42879.8 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2941200
telemt_connections_bad_total 125356
telemt_connections_current 1324
telemt_connections_me_current 1324
telemt_handshake_timeouts_total 63572
telemt_upstream_connect_attempt_total 8619
telemt_upstream_connect_success_total 8478
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 8619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9346
telemt_me_reconnect_success_total 5107
telemt_me_reader_eof_total 5466
telemt_me_idle_close_by_peer_total 5466
telemt_me_route_drop_no_conn_total 1487089
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2516429
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10837
telemt_desync_full_logged_total 3580
telemt_desync_suppressed_total 7257
telemt_desync_frames_bucket_total{bucket="1_2"} 2038
telemt_desync_frames_bucket_total{bucket="3_10"} 4253
telemt_desync_frames_bucket_total{bucket="gt_10"} 4546
telemt_pool_swap_total 35
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5293
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5052
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 2516245
telemt_user_connections_current{user="hello"} 1324
telemt_user_octets_from_client{user="hello"} 38845513518 (36.18 GB)
telemt_user_octets_to_client{user="hello"} 913771144142 (851.02 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 612
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 42857.6 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2874433
telemt_connections_bad_total 469797
telemt_connections_current 1141
telemt_connections_me_current 1141
telemt_handshake_timeouts_total 40574
telemt_upstream_connect_attempt_total 6829
telemt_upstream_connect_success_total 6779
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 6829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3290
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5568
telemt_me_reconnect_success_total 4637
telemt_me_reader_eof_total 4854
telemt_me_idle_close_by_peer_total 4853
telemt_me_route_drop_no_conn_total 1903938
telemt_me_route_drop_channel_closed_total 172
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1991819
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7586
telemt_desync_full_logged_total 2295
telemt_desync_suppressed_total 5291
telemt_desync_frames_bucket_total{bucket="1_2"} 1869
telemt_desync_frames_bucket_total{bucket="3_10"} 2891
telemt_desync_frames_bucket_total{bucket="gt_10"} 2826
telemt_pool_swap_total 41
telemt_me_writer_close_signal_drop_total 68
telemt_me_writer_removed_unexpected_total 4681
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4636
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 1987522
telemt_user_connections_current{user="hello"} 1141
telemt_user_octets_from_client{user="hello"} 29572047340 (27.54 GB)
telemt_user_octets_to_client{user="hello"} 757135108804 (705.14 GB)
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 42845.7 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2493273
telemt_connections_bad_total 108048
telemt_connections_current 996
telemt_connections_me_current 996
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 30441
telemt_upstream_connect_attempt_total 53810
telemt_upstream_connect_success_total 49628
telemt_upstream_connect_fail_total 4182
telemt_upstream_connect_attempts_per_request{bucket="1"} 53810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7117
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 522
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4182
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7945
telemt_me_reconnect_success_total 5165
telemt_me_reader_eof_total 5366
telemt_me_idle_close_by_peer_total 5365
telemt_me_route_drop_no_conn_total 1853318
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2096082
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8225
telemt_desync_full_logged_total 2595
telemt_desync_suppressed_total 5630
telemt_desync_frames_bucket_total{bucket="1_2"} 2017
telemt_desync_frames_bucket_total{bucket="3_10"} 2987
telemt_desync_frames_bucket_total{bucket="gt_10"} 3221
telemt_pool_swap_total 28
telemt_me_writer_close_signal_drop_total 404
telemt_me_writer_removed_unexpected_total 5750
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5161
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 585
telemt_user_connections_total{user="hello"} 2137233
telemt_user_connections_current{user="hello"} 996
telemt_user_octets_from_client{user="hello"} 35143970963 (32.73 GB)
telemt_user_octets_to_client{user="hello"} 598876230367 (557.75 GB)
telemt_user_msgs_from_client{user="hello"} 239211
telemt_user_msgs_to_client{user="hello"} 1739348
telemt_user_unique_ips_current{user="hello"} 407
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 96568.9 (26h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6213843
telemt_connections_bad_total 1039738
telemt_connections_current 1220
telemt_connections_me_current 1220
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 111942
telemt_upstream_connect_attempt_total 126803
telemt_upstream_connect_success_total 93520
telemt_upstream_connect_fail_total 33283
telemt_upstream_connect_attempts_per_request{bucket="1"} 126803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12138
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1430
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33283
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78037
telemt_me_reconnect_success_total 12369
telemt_me_reader_eof_total 13332
telemt_me_idle_close_by_peer_total 13318
telemt_me_route_drop_no_conn_total 2780865
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4394697
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
telemt_desync_total 19342
telemt_desync_full_logged_total 6113
telemt_desync_suppressed_total 13229
telemt_desync_frames_bucket_total{bucket="1_2"} 3373
telemt_desync_frames_bucket_total{bucket="3_10"} 7947
telemt_desync_frames_bucket_total{bucket="gt_10"} 8022
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 12673
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12344
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 4469912
telemt_user_connections_current{user="hello"} 1220
telemt_user_octets_from_client{user="hello"} 69509181064 (64.74 GB)
telemt_user_octets_to_client{user="hello"} 1725040699708 (1.57 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 511
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 42808.8 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 691439
telemt_connections_bad_total 71346
telemt_connections_current 325
telemt_connections_me_current 325
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12929
telemt_upstream_connect_attempt_total 12881
telemt_upstream_connect_success_total 12551
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 12881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6531
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 6062
telemt_me_reconnect_success_total 5957
telemt_me_reader_eof_total 6236
telemt_me_idle_close_by_peer_total 6233
telemt_me_route_drop_no_conn_total 463132
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 569325
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
telemt_desync_total 1397
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 874
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 37
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6010
telemt_me_writer_restored_same_endpoint_total 5948
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 557469
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 7164320307 (6.67 GB)
telemt_user_octets_to_client{user="hello"} 136298674166 (126.94 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 42810.1 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1980317
telemt_connections_bad_total 117958
telemt_connections_current 1061
telemt_connections_me_current 1061
telemt_handshake_timeouts_total 36677
telemt_upstream_connect_attempt_total 7528
telemt_upstream_connect_success_total 7472
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 7528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3417
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5360
telemt_me_reconnect_success_total 5321
telemt_me_reader_eof_total 5613
telemt_me_idle_close_by_peer_total 5613
telemt_me_route_drop_no_conn_total 732317
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1706922
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9037
telemt_desync_full_logged_total 2898
telemt_desync_suppressed_total 6139
telemt_desync_frames_bucket_total{bucket="1_2"} 1676
telemt_desync_frames_bucket_total{bucket="3_10"} 3185
telemt_desync_frames_bucket_total{bucket="gt_10"} 4176
telemt_pool_swap_total 42
telemt_me_writer_close_signal_drop_total 37
telemt_me_writer_removed_unexpected_total 5404
telemt_me_writer_restored_same_endpoint_total 5304
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 1706039
telemt_user_connections_current{user="hello"} 1061
telemt_user_octets_from_client{user="hello"} 29364199828 (27.35 GB)
telemt_user_octets_to_client{user="hello"} 865668984028 (806.22 GB)
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 76
```