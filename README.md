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

# Server Metrics 2026-03-19 12:32:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 53035.6 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1323962
telemt_connections_bad_total 105665
telemt_connections_current 1865
telemt_connections_me_current 1865
telemt_handshake_timeouts_total 46990
telemt_upstream_connect_attempt_total 10150
telemt_upstream_connect_success_total 9979
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 10150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 9218
telemt_me_reconnect_success_total 7324
telemt_me_reader_eof_total 7747
telemt_me_idle_close_by_peer_total 7744
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 549828
telemt_me_route_drop_channel_closed_total 243
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1046283
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5752
telemt_desync_full_logged_total 1777
telemt_desync_suppressed_total 3975
telemt_desync_frames_bucket_total{bucket="1_2"} 1825
telemt_desync_frames_bucket_total{bucket="3_10"} 2061
telemt_desync_frames_bucket_total{bucket="gt_10"} 1866
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 7490
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 7302
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 1040057
telemt_user_connections_current{user="hello"} 1865
telemt_user_octets_from_client{user="hello"} 16253564016 (15.14 GB)
telemt_user_octets_to_client{user="hello"} 315117036024 (293.48 GB)
telemt_user_unique_ips_current{user="hello"} 602
telemt_user_unique_ips_recent_window{user="hello"} 292
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 53040.5 (14h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3768321
telemt_connections_bad_total 244909
telemt_connections_current 3748
telemt_connections_me_current 3748
telemt_handshake_timeouts_total 64507
telemt_upstream_connect_attempt_total 9838
telemt_upstream_connect_success_total 9654
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 9838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 18374
telemt_me_reconnect_success_total 6962
telemt_me_reader_eof_total 7635
telemt_me_idle_close_by_peer_total 7634
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 3150933
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3175349
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12093
telemt_desync_full_logged_total 4039
telemt_desync_suppressed_total 8054
telemt_desync_frames_bucket_total{bucket="1_2"} 2334
telemt_desync_frames_bucket_total{bucket="3_10"} 4731
telemt_desync_frames_bucket_total{bucket="gt_10"} 5028
telemt_pool_swap_total 34
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 7443
telemt_me_refill_failed_total 356
telemt_me_writer_restored_same_endpoint_total 6937
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 481
telemt_user_connections_total{user="hello"} 3174943
telemt_user_connections_current{user="hello"} 3748
telemt_user_octets_from_client{user="hello"} 39475938372 (36.76 GB)
telemt_user_octets_to_client{user="hello"} 903672069088 (841.61 GB)
telemt_user_unique_ips_current{user="hello"} 1330
telemt_user_unique_ips_recent_window{user="hello"} 636
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 53037.6 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2825544
telemt_connections_bad_total 323901
telemt_connections_current 3198
telemt_connections_me_current 3198
telemt_handshake_timeouts_total 54459
telemt_upstream_connect_attempt_total 9588
telemt_upstream_connect_success_total 9588
telemt_upstream_connect_attempts_per_request{bucket="1"} 9588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4581
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 9283
telemt_me_reconnect_success_total 6897
telemt_me_reader_eof_total 7340
telemt_me_idle_close_by_peer_total 7338
telemt_me_route_drop_no_conn_total 1788457
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2237485
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9339
telemt_desync_full_logged_total 2930
telemt_desync_suppressed_total 6409
telemt_desync_frames_bucket_total{bucket="1_2"} 2196
telemt_desync_frames_bucket_total{bucket="3_10"} 3393
telemt_desync_frames_bucket_total{bucket="gt_10"} 3750
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7087
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 6881
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 2235067
telemt_user_connections_current{user="hello"} 3198
telemt_user_octets_from_client{user="hello"} 30135620392 (28.07 GB)
telemt_user_octets_to_client{user="hello"} 931281056996 (867.32 GB)
telemt_user_unique_ips_current{user="hello"} 1104
telemt_user_unique_ips_recent_window{user="hello"} 545
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 53090.7 (14h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2957423
telemt_connections_bad_total 147013
telemt_connections_current 3270
telemt_connections_me_current 3270
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 68873
telemt_upstream_connect_attempt_total 24694
telemt_upstream_connect_success_total 24169
telemt_upstream_connect_fail_total 525
telemt_upstream_connect_attempts_per_request{bucket="1"} 24694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5829
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 434
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 525
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 11618
telemt_me_reconnect_success_total 6801
telemt_me_reader_eof_total 7222
telemt_me_idle_close_by_peer_total 7221
telemt_me_route_drop_no_conn_total 2251141
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2328879
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
telemt_desync_total 7849
telemt_desync_full_logged_total 2610
telemt_desync_suppressed_total 5239
telemt_desync_frames_bucket_total{bucket="1_2"} 1671
telemt_desync_frames_bucket_total{bucket="3_10"} 3087
telemt_desync_frames_bucket_total{bucket="gt_10"} 3091
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7417
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6777
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 311
telemt_me_writer_removed_unexpected_minus_restored_total 616
telemt_user_connections_total{user="hello"} 2341382
telemt_user_connections_current{user="hello"} 3270
telemt_user_octets_from_client{user="hello"} 25168860920 (23.44 GB)
telemt_user_octets_to_client{user="hello"} 587532599229 (547.18 GB)
telemt_user_msgs_from_client{user="hello"} 46376
telemt_user_msgs_to_client{user="hello"} 105213
telemt_user_unique_ips_current{user="hello"} 1026
telemt_user_unique_ips_recent_window{user="hello"} 697
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 53034.4 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3502368
telemt_connections_bad_total 717015
telemt_connections_current 3700
telemt_connections_me_current 3700
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 68126
telemt_upstream_connect_attempt_total 61270
telemt_upstream_connect_success_total 58791
telemt_upstream_connect_fail_total 2479
telemt_upstream_connect_attempts_per_request{bucket="1"} 61270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6727
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2479
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 70024
telemt_me_reconnect_success_total 6975
telemt_me_reader_eof_total 7285
telemt_me_idle_close_by_peer_total 7282
telemt_me_route_drop_no_conn_total 1564490
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2324342
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
telemt_desync_total 9896
telemt_desync_full_logged_total 3071
telemt_desync_suppressed_total 6825
telemt_desync_frames_bucket_total{bucket="1_2"} 1818
telemt_desync_frames_bucket_total{bucket="3_10"} 4244
telemt_desync_frames_bucket_total{bucket="gt_10"} 3834
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 7091
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 6951
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 2373224
telemt_user_connections_current{user="hello"} 3700
telemt_user_octets_from_client{user="hello"} 37735896863 (35.14 GB)
telemt_user_octets_to_client{user="hello"} 871514714884 (811.66 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1154
telemt_user_unique_ips_recent_window{user="hello"} 600
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 53047.2 (14h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 586606
telemt_connections_bad_total 20537
telemt_connections_current 1082
telemt_connections_me_current 1082
telemt_handshake_timeouts_total 4841
telemt_upstream_connect_attempt_total 13059
telemt_upstream_connect_success_total 12714
telemt_upstream_connect_fail_total 345
telemt_upstream_connect_attempts_per_request{bucket="1"} 13059
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6475
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 345
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 17639
telemt_me_reconnect_success_total 10045
telemt_me_reader_eof_total 10700
telemt_me_idle_close_by_peer_total 10700
telemt_me_route_drop_no_conn_total 303325
telemt_me_route_drop_channel_closed_total 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 533154
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1345
telemt_desync_full_logged_total 466
telemt_desync_suppressed_total 879
telemt_desync_frames_bucket_total{bucket="1_2"} 261
telemt_desync_frames_bucket_total{bucket="3_10"} 552
telemt_desync_frames_bucket_total{bucket="gt_10"} 532
telemt_pool_swap_total 25
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 10377
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 10014
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 533088
telemt_user_connections_current{user="hello"} 1082
telemt_user_octets_from_client{user="hello"} 8475321852 (7.89 GB)
telemt_user_octets_to_client{user="hello"} 189576357204 (176.56 GB)
telemt_user_unique_ips_current{user="hello"} 369
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 53036.8 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2343319
telemt_connections_bad_total 185902
telemt_connections_current 3350
telemt_connections_me_current 3350
telemt_handshake_timeouts_total 74930
telemt_upstream_connect_attempt_total 10669
telemt_upstream_connect_success_total 10668
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4886
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 10490
telemt_me_reconnect_success_total 7981
telemt_me_reader_eof_total 8469
telemt_me_idle_close_by_peer_total 8468
telemt_me_route_drop_no_conn_total 1202169
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1974835
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10774
telemt_desync_full_logged_total 3406
telemt_desync_suppressed_total 7368
telemt_desync_frames_bucket_total{bucket="1_2"} 2069
telemt_desync_frames_bucket_total{bucket="3_10"} 4081
telemt_desync_frames_bucket_total{bucket="gt_10"} 4624
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8162
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 7966
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 1973551
telemt_user_connections_current{user="hello"} 3350
telemt_user_octets_from_client{user="hello"} 25685029320 (23.92 GB)
telemt_user_octets_to_client{user="hello"} 872472752424 (812.55 GB)
telemt_user_unique_ips_current{user="hello"} 1055
telemt_user_unique_ips_recent_window{user="hello"} 499
```