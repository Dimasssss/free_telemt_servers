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

# Server Metrics 2026-03-19 18:07:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 2973.3 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93819
telemt_connections_bad_total 2819
telemt_connections_current 1657
telemt_connections_me_current 1657
telemt_handshake_timeouts_total 892
telemt_upstream_connect_attempt_total 463
telemt_upstream_connect_success_total 454
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 215
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 258
telemt_me_reconnect_success_total 257
telemt_me_reader_eof_total 252
telemt_me_idle_close_by_peer_total 252
telemt_me_route_drop_no_conn_total 32670
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82139
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 385
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 257
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 182
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 24
telemt_me_writer_removed_unexpected_total 268
telemt_me_writer_restored_same_endpoint_total 244
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 82292
telemt_user_connections_current{user="hello"} 1657
telemt_user_octets_from_client{user="hello"} 1378605700 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 28335665344 (26.39 GB)
telemt_user_unique_ips_current{user="hello"} 480
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 19428.9 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1947033
telemt_connections_bad_total 96753
telemt_connections_current 4146
telemt_connections_me_current 4146
telemt_handshake_timeouts_total 36375
telemt_upstream_connect_attempt_total 4513
telemt_upstream_connect_success_total 4459
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 4513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1447
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 6447
telemt_me_reconnect_success_total 2222
telemt_me_reader_eof_total 2404
telemt_me_idle_close_by_peer_total 2404
telemt_me_route_drop_no_conn_total 1126083
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1615198
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6444
telemt_desync_full_logged_total 2034
telemt_desync_suppressed_total 4410
telemt_desync_frames_bucket_total{bucket="1_2"} 1232
telemt_desync_frames_bucket_total{bucket="3_10"} 2567
telemt_desync_frames_bucket_total{bucket="gt_10"} 2645
telemt_pool_swap_total 13
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 2368
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 2167
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 1615187
telemt_user_connections_current{user="hello"} 4146
telemt_user_octets_from_client{user="hello"} 23748173014 (22.12 GB)
telemt_user_octets_to_client{user="hello"} 519419607958 (483.75 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1327
telemt_user_unique_ips_recent_window{user="hello"} 531
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 19407.4 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1792724
telemt_connections_bad_total 212589
telemt_connections_current 2823
telemt_connections_me_current 2823
telemt_handshake_timeouts_total 19262
telemt_upstream_connect_attempt_total 3094
telemt_upstream_connect_success_total 3072
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1412
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2982
telemt_me_reconnect_success_total 2064
telemt_me_reader_eof_total 2098
telemt_me_idle_close_by_peer_total 2097
telemt_me_route_drop_no_conn_total 1572625
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1363007
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4339
telemt_desync_full_logged_total 1292
telemt_desync_suppressed_total 3047
telemt_desync_frames_bucket_total{bucket="1_2"} 1128
telemt_desync_frames_bucket_total{bucket="3_10"} 1627
telemt_desync_frames_bucket_total{bucket="gt_10"} 1584
telemt_pool_swap_total 15
telemt_me_writer_close_signal_drop_total 45
telemt_me_writer_removed_unexpected_total 2054
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 2063
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 1359981
telemt_user_connections_current{user="hello"} 2823
telemt_user_octets_from_client{user="hello"} 17192951940 (16.01 GB)
telemt_user_octets_to_client{user="hello"} 422546898596 (393.53 GB)
telemt_user_unique_ips_current{user="hello"} 981
telemt_user_unique_ips_recent_window{user="hello"} 371
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 19395.1 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1645341
telemt_connections_bad_total 59185
telemt_connections_current 2747
telemt_connections_me_current 2747
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 22935
telemt_upstream_connect_attempt_total 25079
telemt_upstream_connect_success_total 23903
telemt_upstream_connect_fail_total 1176
telemt_upstream_connect_attempts_per_request{bucket="1"} 25079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3914
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1176
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 4840
telemt_me_reconnect_success_total 2470
telemt_me_reader_eof_total 2548
telemt_me_idle_close_by_peer_total 2547
telemt_me_route_drop_no_conn_total 1417542
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1416180
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5642
telemt_desync_full_logged_total 1776
telemt_desync_suppressed_total 3866
telemt_desync_frames_bucket_total{bucket="1_2"} 1493
telemt_desync_frames_bucket_total{bucket="3_10"} 2074
telemt_desync_frames_bucket_total{bucket="gt_10"} 2075
telemt_pool_swap_total 7
telemt_me_writer_close_signal_drop_total 200
telemt_me_writer_removed_unexpected_total 2875
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 2466
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 405
telemt_user_connections_total{user="hello"} 1435532
telemt_user_connections_current{user="hello"} 2747
telemt_user_octets_from_client{user="hello"} 26053221073 (24.26 GB)
telemt_user_octets_to_client{user="hello"} 313493629881 (291.96 GB)
telemt_user_msgs_from_client{user="hello"} 49930
telemt_user_msgs_to_client{user="hello"} 93819
telemt_user_unique_ips_current{user="hello"} 931
telemt_user_unique_ips_recent_window{user="hello"} 424
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 73117.8 (20h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5300974
telemt_connections_bad_total 944993
telemt_connections_current 3309
telemt_connections_me_current 3309
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 98069
telemt_upstream_connect_attempt_total 64720
telemt_upstream_connect_success_total 62228
telemt_upstream_connect_fail_total 2492
telemt_upstream_connect_attempts_per_request{bucket="1"} 64720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8323
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1045
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2492
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 74777
telemt_me_reconnect_success_total 9369
telemt_me_reader_eof_total 9875
telemt_me_idle_close_by_peer_total 9872
telemt_me_route_drop_no_conn_total 2466149
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3700664
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
telemt_desync_total 16103
telemt_desync_full_logged_total 4909
telemt_desync_suppressed_total 11194
telemt_desync_frames_bucket_total{bucket="1_2"} 2641
telemt_desync_frames_bucket_total{bucket="3_10"} 6731
telemt_desync_frames_bucket_total{bucket="gt_10"} 6731
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 9611
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 9345
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 3748782
telemt_user_connections_current{user="hello"} 3309
telemt_user_octets_from_client{user="hello"} 58410466303 (54.40 GB)
telemt_user_octets_to_client{user="hello"} 1373720921160 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1147
telemt_user_unique_ips_recent_window{user="hello"} 501
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 19359.1 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 457878
telemt_connections_bad_total 29991
telemt_connections_current 707
telemt_connections_me_current 707
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 9551
telemt_upstream_connect_attempt_total 6862
telemt_upstream_connect_success_total 6666
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 6862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3820
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 539
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 410
telemt_me_reconnect_attempts_total 2722
telemt_me_reconnect_success_total 2670
telemt_me_reader_eof_total 2730
telemt_me_idle_close_by_peer_total 2729
telemt_me_route_drop_no_conn_total 314934
telemt_me_route_drop_channel_closed_total 97
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 362199
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
telemt_desync_total 1003
telemt_desync_full_logged_total 313
telemt_desync_suppressed_total 690
telemt_desync_frames_bucket_total{bucket="1_2"} 152
telemt_desync_frames_bucket_total{bucket="3_10"} 405
telemt_desync_frames_bucket_total{bucket="gt_10"} 446
telemt_pool_swap_total 12
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 104
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 2672
telemt_me_writer_restored_same_endpoint_total 2661
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 380413
telemt_user_connections_current{user="hello"} 707
telemt_user_octets_from_client{user="hello"} 4555335304 (4.24 GB)
telemt_user_octets_to_client{user="hello"} 82966043330 (77.27 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 19359.4 (5h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1288233
telemt_connections_bad_total 84567
telemt_connections_current 3245
telemt_connections_me_current 3245
telemt_handshake_timeouts_total 23218
telemt_upstream_connect_attempt_total 3239
telemt_upstream_connect_success_total 3215
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 3239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1469
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 2226
telemt_me_reconnect_success_total 2201
telemt_me_reader_eof_total 2305
telemt_me_idle_close_by_peer_total 2305
telemt_me_route_drop_no_conn_total 498591
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1109053
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6038
telemt_desync_full_logged_total 1828
telemt_desync_suppressed_total 4210
telemt_desync_frames_bucket_total{bucket="1_2"} 1186
telemt_desync_frames_bucket_total{bucket="3_10"} 2092
telemt_desync_frames_bucket_total{bucket="gt_10"} 2760
telemt_pool_swap_total 16
telemt_me_writer_close_signal_drop_total 30
telemt_me_writer_removed_unexpected_total 2246
telemt_me_writer_restored_same_endpoint_total 2184
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 1108561
telemt_user_connections_current{user="hello"} 3245
telemt_user_octets_from_client{user="hello"} 17250880008 (16.07 GB)
telemt_user_octets_to_client{user="hello"} 487160977128 (453.70 GB)
telemt_user_unique_ips_current{user="hello"} 1026
telemt_user_unique_ips_recent_window{user="hello"} 418
```