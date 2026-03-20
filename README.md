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

# Server Metrics 2026-03-20 00:07:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 24588.7 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 493212
telemt_connections_bad_total 31903
telemt_connections_current 787
telemt_connections_me_current 787
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 7379
telemt_upstream_connect_attempt_total 5375
telemt_upstream_connect_success_total 5303
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 5375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2117
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 2961
telemt_me_reconnect_success_total 2932
telemt_me_reader_eof_total 3083
telemt_me_idle_close_by_peer_total 3082
telemt_me_route_drop_no_conn_total 144788
telemt_me_route_drop_channel_closed_total 55
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 390542
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1987
telemt_desync_full_logged_total 704
telemt_desync_suppressed_total 1283
telemt_desync_frames_bucket_total{bucket="1_2"} 410
telemt_desync_frames_bucket_total{bucket="3_10"} 654
telemt_desync_frames_bucket_total{bucket="gt_10"} 923
telemt_pool_swap_total 27
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 2949
telemt_me_writer_restored_same_endpoint_total 2919
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 391952
telemt_user_connections_current{user="hello"} 787
telemt_user_octets_from_client{user="hello"} 29127908872 (27.13 GB)
telemt_user_octets_to_client{user="hello"} 143138187417 (133.31 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 41043.2 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2908973
telemt_connections_bad_total 123359
telemt_connections_current 1390
telemt_connections_me_current 1390
telemt_handshake_timeouts_total 61760
telemt_upstream_connect_attempt_total 8174
telemt_upstream_connect_success_total 8041
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 8174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8995
telemt_me_reconnect_success_total 4758
telemt_me_reader_eof_total 5101
telemt_me_idle_close_by_peer_total 5101
telemt_me_route_drop_no_conn_total 1478535
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2488699
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10783
telemt_desync_full_logged_total 3565
telemt_desync_suppressed_total 7218
telemt_desync_frames_bucket_total{bucket="1_2"} 2025
telemt_desync_frames_bucket_total{bucket="3_10"} 4232
telemt_desync_frames_bucket_total{bucket="gt_10"} 4526
telemt_pool_swap_total 34
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 4942
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4703
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 2488523
telemt_user_connections_current{user="hello"} 1390
telemt_user_octets_from_client{user="hello"} 38559224378 (35.91 GB)
telemt_user_octets_to_client{user="hello"} 900698403466 (838.84 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 613
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 41021.3 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2837740
telemt_connections_bad_total 468382
telemt_connections_current 1106
telemt_connections_me_current 1106
telemt_handshake_timeouts_total 38671
telemt_upstream_connect_attempt_total 6517
telemt_upstream_connect_success_total 6468
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 6517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5343
telemt_me_reconnect_success_total 4412
telemt_me_reader_eof_total 4613
telemt_me_idle_close_by_peer_total 4612
telemt_me_route_drop_no_conn_total 1895079
telemt_me_route_drop_channel_closed_total 170
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1970374
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7530
telemt_desync_full_logged_total 2278
telemt_desync_suppressed_total 5252
telemt_desync_frames_bucket_total{bucket="1_2"} 1852
telemt_desync_frames_bucket_total{bucket="3_10"} 2863
telemt_desync_frames_bucket_total{bucket="gt_10"} 2815
telemt_pool_swap_total 39
telemt_me_writer_close_signal_drop_total 64
telemt_me_writer_removed_unexpected_total 4454
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4411
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 1966119
telemt_user_connections_current{user="hello"} 1106
telemt_user_octets_from_client{user="hello"} 29392779192 (27.37 GB)
telemt_user_octets_to_client{user="hello"} 746573602436 (695.30 GB)
telemt_user_unique_ips_current{user="hello"} 484
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 41009.1 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2470446
telemt_connections_bad_total 107184
telemt_connections_current 990
telemt_connections_me_current 990
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 30303
telemt_upstream_connect_attempt_total 53495
telemt_upstream_connect_success_total 49324
telemt_upstream_connect_fail_total 4171
telemt_upstream_connect_attempts_per_request{bucket="1"} 53495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6976
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 520
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4171
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7717
telemt_me_reconnect_success_total 4947
telemt_me_reader_eof_total 5132
telemt_me_idle_close_by_peer_total 5131
telemt_me_route_drop_no_conn_total 1847131
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2077464
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8185
telemt_desync_full_logged_total 2582
telemt_desync_suppressed_total 5603
telemt_desync_frames_bucket_total{bucket="1_2"} 2007
telemt_desync_frames_bucket_total{bucket="3_10"} 2976
telemt_desync_frames_bucket_total{bucket="gt_10"} 3202
telemt_pool_swap_total 26
telemt_me_writer_close_signal_drop_total 404
telemt_me_writer_removed_unexpected_total 5524
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 4943
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 577
telemt_user_connections_total{user="hello"} 2118617
telemt_user_connections_current{user="hello"} 990
telemt_user_octets_from_client{user="hello"} 34873980883 (32.48 GB)
telemt_user_octets_to_client{user="hello"} 581315683611 (541.39 GB)
telemt_user_msgs_from_client{user="hello"} 239211
telemt_user_msgs_to_client{user="hello"} 1739348
telemt_user_unique_ips_current{user="hello"} 394
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 94732.4 (26h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6186650
telemt_connections_bad_total 1038303
telemt_connections_current 1100
telemt_connections_me_current 1100
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 111305
telemt_upstream_connect_attempt_total 126483
telemt_upstream_connect_success_total 93201
telemt_upstream_connect_fail_total 33282
telemt_upstream_connect_attempts_per_request{bucket="1"} 126483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11976
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1425
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33282
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 77806
telemt_me_reconnect_success_total 12141
telemt_me_reader_eof_total 13092
telemt_me_idle_close_by_peer_total 13078
telemt_me_route_drop_no_conn_total 2774408
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4370817
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
telemt_desync_total 19216
telemt_desync_full_logged_total 6053
telemt_desync_suppressed_total 13163
telemt_desync_frames_bucket_total{bucket="1_2"} 3360
telemt_desync_frames_bucket_total{bucket="3_10"} 7888
telemt_desync_frames_bucket_total{bucket="gt_10"} 7968
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 12444
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12116
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 303
telemt_user_connections_total{user="hello"} 4446032
telemt_user_connections_current{user="hello"} 1100
telemt_user_octets_from_client{user="hello"} 68366417048 (63.67 GB)
telemt_user_octets_to_client{user="hello"} 1716479011692 (1.56 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 494
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 40972.3 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 682650
telemt_connections_bad_total 69456
telemt_connections_current 306
telemt_connections_me_current 306
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12878
telemt_upstream_connect_attempt_total 12445
telemt_upstream_connect_success_total 12115
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 12445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6263
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 660
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 5712
telemt_me_reconnect_success_total 5607
telemt_me_reader_eof_total 5856
telemt_me_idle_close_by_peer_total 5853
telemt_me_route_drop_no_conn_total 459395
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 562912
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
telemt_pool_swap_total 35
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 5656
telemt_me_writer_restored_same_endpoint_total 5598
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 551056
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 7125666871 (6.64 GB)
telemt_user_octets_to_client{user="hello"} 134087331114 (124.88 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 40973.6 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1961985
telemt_connections_bad_total 117942
telemt_connections_current 1155
telemt_connections_me_current 1155
telemt_handshake_timeouts_total 36402
telemt_upstream_connect_attempt_total 7172
telemt_upstream_connect_success_total 7118
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 7172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5092
telemt_me_reconnect_success_total 5054
telemt_me_reader_eof_total 5333
telemt_me_idle_close_by_peer_total 5333
telemt_me_route_drop_no_conn_total 726578
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1689620
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8995
telemt_desync_full_logged_total 2877
telemt_desync_suppressed_total 6118
telemt_desync_frames_bucket_total{bucket="1_2"} 1657
telemt_desync_frames_bucket_total{bucket="3_10"} 3168
telemt_desync_frames_bucket_total{bucket="gt_10"} 4170
telemt_pool_swap_total 40
telemt_me_writer_close_signal_drop_total 37
telemt_me_writer_removed_unexpected_total 5135
telemt_me_writer_restored_same_endpoint_total 5037
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 1688755
telemt_user_connections_current{user="hello"} 1155
telemt_user_octets_from_client{user="hello"} 28536689896 (26.58 GB)
telemt_user_octets_to_client{user="hello"} 857716187944 (798.81 GB)
telemt_user_unique_ips_current{user="hello"} 484
telemt_user_unique_ips_recent_window{user="hello"} 101
```