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

# Server Metrics 2026-03-19 12:42:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 49.6 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4019
telemt_connections_bad_total 34
telemt_connections_current 1572
telemt_connections_me_current 1572
telemt_upstream_connect_attempt_total 93
telemt_upstream_connect_success_total 83
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 92
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 20
telemt_me_reconnect_success_total 12
telemt_me_route_drop_no_conn_total 1038
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3795
telemt_me_writer_pick_total{mode="p2c",result="full"} 54
telemt_me_writer_pick_total{mode="p2c",result="closed"} 152
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 2
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 220
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 3797
telemt_user_connections_current{user="hello"} 1572
telemt_user_octets_from_client{user="hello"} 16173540 (15.42 MB)
telemt_user_octets_to_client{user="hello"} 254281524 (242.50 MB)
telemt_user_unique_ips_current{user="hello"} 510
telemt_user_unique_ips_recent_window{user="hello"} 572
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 53653.5 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3836858
telemt_connections_bad_total 255643
telemt_connections_current 3905
telemt_connections_me_current 3905
telemt_handshake_timeouts_total 64940
telemt_upstream_connect_attempt_total 9947
telemt_upstream_connect_success_total 9762
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 9947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 18437
telemt_me_reconnect_success_total 7024
telemt_me_reader_eof_total 7701
telemt_me_idle_close_by_peer_total 7700
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 3171404
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3227596
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12302
telemt_desync_full_logged_total 4104
telemt_desync_suppressed_total 8198
telemt_desync_frames_bucket_total{bucket="1_2"} 2372
telemt_desync_frames_bucket_total{bucket="3_10"} 4819
telemt_desync_frames_bucket_total{bucket="gt_10"} 5111
telemt_pool_swap_total 35
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 7505
telemt_me_refill_failed_total 356
telemt_me_writer_restored_same_endpoint_total 6999
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 481
telemt_user_connections_total{user="hello"} 3227178
telemt_user_connections_current{user="hello"} 3905
telemt_user_octets_from_client{user="hello"} 40052023708 (37.30 GB)
telemt_user_octets_to_client{user="hello"} 918374854828 (855.30 GB)
telemt_user_unique_ips_current{user="hello"} 1361
telemt_user_unique_ips_recent_window{user="hello"} 601
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 53650.1 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2882501
telemt_connections_bad_total 328759
telemt_connections_current 3116
telemt_connections_me_current 3116
telemt_handshake_timeouts_total 55066
telemt_upstream_connect_attempt_total 9689
telemt_upstream_connect_success_total 9689
telemt_upstream_connect_attempts_per_request{bucket="1"} 9689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 9340
telemt_me_reconnect_success_total 6952
telemt_me_reader_eof_total 7400
telemt_me_idle_close_by_peer_total 7398
telemt_me_route_drop_no_conn_total 1806940
telemt_me_route_drop_channel_closed_total 99
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2277693
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9569
telemt_desync_full_logged_total 2982
telemt_desync_suppressed_total 6587
telemt_desync_frames_bucket_total{bucket="1_2"} 2275
telemt_desync_frames_bucket_total{bucket="3_10"} 3481
telemt_desync_frames_bucket_total{bucket="gt_10"} 3813
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 7143
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 6936
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 2275257
telemt_user_connections_current{user="hello"} 3116
telemt_user_octets_from_client{user="hello"} 30804233316 (28.69 GB)
telemt_user_octets_to_client{user="hello"} 946203514868 (881.22 GB)
telemt_user_unique_ips_current{user="hello"} 1088
telemt_user_unique_ips_recent_window{user="hello"} 492
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 53703.9 (14h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3029174
telemt_connections_bad_total 149404
telemt_connections_current 3016
telemt_connections_me_current 3016
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 69517
telemt_upstream_connect_attempt_total 24808
telemt_upstream_connect_success_total 24274
telemt_upstream_connect_fail_total 534
telemt_upstream_connect_attempts_per_request{bucket="1"} 24808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5879
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 435
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 534
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 11687
telemt_me_reconnect_success_total 6862
telemt_me_reader_eof_total 7290
telemt_me_idle_close_by_peer_total 7289
telemt_me_route_drop_no_conn_total 2386658
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2392741
telemt_me_writer_pick_total{mode="p2c",result="full"} 113
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_writer_pick_blocking_fallback_total 103
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8035
telemt_desync_full_logged_total 2669
telemt_desync_suppressed_total 5366
telemt_desync_frames_bucket_total{bucket="1_2"} 1716
telemt_desync_frames_bucket_total{bucket="3_10"} 3165
telemt_desync_frames_bucket_total{bucket="gt_10"} 3154
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 7480
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6838
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 311
telemt_me_writer_removed_unexpected_minus_restored_total 618
telemt_user_connections_total{user="hello"} 2405220
telemt_user_connections_current{user="hello"} 3016
telemt_user_octets_from_client{user="hello"} 25646190192 (23.88 GB)
telemt_user_octets_to_client{user="hello"} 596227985745 (555.28 GB)
telemt_user_msgs_from_client{user="hello"} 46376
telemt_user_msgs_to_client{user="hello"} 105213
telemt_user_unique_ips_current{user="hello"} 1030
telemt_user_unique_ips_recent_window{user="hello"} 476
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 53647.3 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3551888
telemt_connections_bad_total 718390
telemt_connections_current 3600
telemt_connections_me_current 3600
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 69520
telemt_upstream_connect_attempt_total 61380
telemt_upstream_connect_success_total 58901
telemt_upstream_connect_fail_total 2479
telemt_upstream_connect_attempts_per_request{bucket="1"} 61380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6779
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2479
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 70089
telemt_me_reconnect_success_total 7040
telemt_me_reader_eof_total 7354
telemt_me_idle_close_by_peer_total 7351
telemt_me_route_drop_no_conn_total 1584749
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2368235
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10145
telemt_desync_full_logged_total 3158
telemt_desync_suppressed_total 6987
telemt_desync_frames_bucket_total{bucket="1_2"} 1860
telemt_desync_frames_bucket_total{bucket="3_10"} 4320
telemt_desync_frames_bucket_total{bucket="gt_10"} 3965
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7156
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 7016
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 2417111
telemt_user_connections_current{user="hello"} 3600
telemt_user_octets_from_client{user="hello"} 38200493467 (35.58 GB)
telemt_user_octets_to_client{user="hello"} 883933052072 (823.23 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1145
telemt_user_unique_ips_recent_window{user="hello"} 539
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 53660.5 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 598012
telemt_connections_bad_total 21255
telemt_connections_current 1019
telemt_connections_me_current 1019
telemt_handshake_timeouts_total 5027
telemt_upstream_connect_attempt_total 13217
telemt_upstream_connect_success_total 12870
telemt_upstream_connect_fail_total 347
telemt_upstream_connect_attempts_per_request{bucket="1"} 13217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6555
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 347
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 17751
telemt_me_reconnect_success_total 10157
telemt_me_reader_eof_total 10814
telemt_me_idle_close_by_peer_total 10814
telemt_me_route_drop_no_conn_total 308903
telemt_me_route_drop_channel_closed_total 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 542958
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1369
telemt_desync_full_logged_total 476
telemt_desync_suppressed_total 893
telemt_desync_frames_bucket_total{bucket="1_2"} 261
telemt_desync_frames_bucket_total{bucket="3_10"} 566
telemt_desync_frames_bucket_total{bucket="gt_10"} 542
telemt_pool_swap_total 25
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 10491
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 10126
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 334
telemt_user_connections_total{user="hello"} 542885
telemt_user_connections_current{user="hello"} 1019
telemt_user_octets_from_client{user="hello"} 8591527772 (8.00 GB)
telemt_user_octets_to_client{user="hello"} 191544577300 (178.39 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 53649.7 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2382887
telemt_connections_bad_total 187460
telemt_connections_current 3145
telemt_connections_me_current 3145
telemt_handshake_timeouts_total 75136
telemt_upstream_connect_attempt_total 10785
telemt_upstream_connect_success_total 10784
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4939
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 10562
telemt_me_reconnect_success_total 8052
telemt_me_reader_eof_total 8545
telemt_me_idle_close_by_peer_total 8544
telemt_me_route_drop_no_conn_total 1215550
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2011044
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10936
telemt_desync_full_logged_total 3458
telemt_desync_suppressed_total 7478
telemt_desync_frames_bucket_total{bucket="1_2"} 2099
telemt_desync_frames_bucket_total{bucket="3_10"} 4132
telemt_desync_frames_bucket_total{bucket="gt_10"} 4705
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 8234
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 8037
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 2009734
telemt_user_connections_current{user="hello"} 3145
telemt_user_octets_from_client{user="hello"} 26053867060 (24.26 GB)
telemt_user_octets_to_client{user="hello"} 889808218860 (828.70 GB)
telemt_user_unique_ips_current{user="hello"} 1042
telemt_user_unique_ips_recent_window{user="hello"} 440
```