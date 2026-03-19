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

# Server Metrics 2026-03-19 21:44:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 16018.0 (4h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387794
telemt_connections_bad_total 19305
telemt_connections_current 754
telemt_connections_me_current 754
telemt_handshake_timeouts_total 5675
telemt_upstream_connect_attempt_total 2574
telemt_upstream_connect_success_total 2551
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 2574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 1753
telemt_me_reconnect_success_total 1740
telemt_me_reader_eof_total 1836
telemt_me_idle_close_by_peer_total 1836
telemt_me_route_drop_no_conn_total 118003
telemt_me_route_drop_channel_closed_total 48
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308333
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1676
telemt_desync_full_logged_total 580
telemt_desync_suppressed_total 1096
telemt_desync_frames_bucket_total{bucket="1_2"} 352
telemt_desync_frames_bucket_total{bucket="3_10"} 515
telemt_desync_frames_bucket_total{bucket="gt_10"} 809
telemt_pool_swap_total 17
telemt_me_writer_close_signal_drop_total 32
telemt_me_writer_removed_unexpected_total 1780
telemt_me_writer_restored_same_endpoint_total 1727
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 308603
telemt_user_connections_current{user="hello"} 754
telemt_user_octets_from_client{user="hello"} 11077830392 (10.32 GB)
telemt_user_octets_to_client{user="hello"} 115790631972 (107.84 GB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 32472.3 (9h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2710003
telemt_connections_bad_total 115765
telemt_connections_current 1955
telemt_connections_me_current 1955
telemt_handshake_timeouts_total 53253
telemt_upstream_connect_attempt_total 6651
telemt_upstream_connect_success_total 6545
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 6651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7906
telemt_me_reconnect_success_total 3676
telemt_me_reader_eof_total 3942
telemt_me_idle_close_by_peer_total 3942
telemt_me_route_drop_no_conn_total 1421077
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2311415
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10262
telemt_desync_full_logged_total 3331
telemt_desync_suppressed_total 6931
telemt_desync_frames_bucket_total{bucket="1_2"} 1911
telemt_desync_frames_bucket_total{bucket="3_10"} 4003
telemt_desync_frames_bucket_total{bucket="gt_10"} 4348
telemt_pool_swap_total 24
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 3843
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 3621
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 2311293
telemt_user_connections_current{user="hello"} 1955
telemt_user_octets_from_client{user="hello"} 36441462078 (33.94 GB)
telemt_user_octets_to_client{user="hello"} 821858455866 (765.42 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 816
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 32450.4 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2642526
telemt_connections_bad_total 456714
telemt_connections_current 1555
telemt_connections_me_current 1555
telemt_handshake_timeouts_total 32986
telemt_upstream_connect_attempt_total 5016
telemt_upstream_connect_success_total 4975
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 5015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4268
telemt_me_reconnect_success_total 3342
telemt_me_reader_eof_total 3469
telemt_me_idle_close_by_peer_total 3468
telemt_me_route_drop_no_conn_total 1847581
telemt_me_route_drop_channel_closed_total 165
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1848645
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7083
telemt_desync_full_logged_total 2132
telemt_desync_suppressed_total 4951
telemt_desync_frames_bucket_total{bucket="1_2"} 1783
telemt_desync_frames_bucket_total{bucket="3_10"} 2694
telemt_desync_frames_bucket_total{bucket="gt_10"} 2606
telemt_pool_swap_total 29
telemt_me_writer_close_signal_drop_total 59
telemt_me_writer_removed_unexpected_total 3362
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3341
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1844583
telemt_user_connections_current{user="hello"} 1555
telemt_user_octets_from_client{user="hello"} 28030309928 (26.11 GB)
telemt_user_octets_to_client{user="hello"} 671976028252 (625.83 GB)
telemt_user_unique_ips_current{user="hello"} 628
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 32438.1 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2312493
telemt_connections_bad_total 94800
telemt_connections_current 1466
telemt_connections_me_current 1466
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 29144
telemt_upstream_connect_attempt_total 35217
telemt_upstream_connect_success_total 33502
telemt_upstream_connect_fail_total 1715
telemt_upstream_connect_attempts_per_request{bucket="1"} 35217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5360
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 445
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1715
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 6401
telemt_me_reconnect_success_total 3794
telemt_me_reader_eof_total 3932
telemt_me_idle_close_by_peer_total 3931
telemt_me_route_drop_no_conn_total 1809127
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1970025
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7913
telemt_desync_full_logged_total 2471
telemt_desync_suppressed_total 5442
telemt_desync_frames_bucket_total{bucket="1_2"} 1950
telemt_desync_frames_bucket_total{bucket="3_10"} 2882
telemt_desync_frames_bucket_total{bucket="gt_10"} 3081
telemt_pool_swap_total 19
telemt_me_writer_close_signal_drop_total 347
telemt_me_writer_removed_unexpected_total 4304
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 3790
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 1996963
telemt_user_connections_current{user="hello"} 1466
telemt_user_octets_from_client{user="hello"} 32939927824 (30.68 GB)
telemt_user_octets_to_client{user="hello"} 505090353515 (470.40 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 559
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 86161.4 (23h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5985338
telemt_connections_bad_total 1031185
telemt_connections_current 1846
telemt_connections_me_current 1846
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 108477
telemt_upstream_connect_attempt_total 66622
telemt_upstream_connect_success_total 64119
telemt_upstream_connect_fail_total 2503
telemt_upstream_connect_attempts_per_request{bucket="1"} 66622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9268
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1057
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2503
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 76063
telemt_me_reconnect_success_total 10645
telemt_me_reader_eof_total 11237
telemt_me_idle_close_by_peer_total 11234
telemt_me_route_drop_no_conn_total 2731018
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4244797
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
telemt_desync_total 18687
telemt_desync_full_logged_total 5800
telemt_desync_suppressed_total 12887
telemt_desync_frames_bucket_total{bucket="1_2"} 3240
telemt_desync_frames_bucket_total{bucket="3_10"} 7706
telemt_desync_frames_bucket_total{bucket="gt_10"} 7741
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 10908
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 10621
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 4292846
telemt_user_connections_current{user="hello"} 1846
telemt_user_octets_from_client{user="hello"} 66662031331 (62.08 GB)
telemt_user_octets_to_client{user="hello"} 1656772473816 (1.51 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 703
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 32401.3 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 618242
telemt_connections_bad_total 48908
telemt_connections_current 421
telemt_connections_me_current 421
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 11818
telemt_upstream_connect_attempt_total 9077
telemt_upstream_connect_success_total 8866
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 9077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5097
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 564
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4333
telemt_me_reconnect_success_total 4253
telemt_me_reader_eof_total 4425
telemt_me_idle_close_by_peer_total 4423
telemt_me_route_drop_no_conn_total 415581
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 503812
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
telemt_desync_total 1348
telemt_desync_full_logged_total 504
telemt_desync_suppressed_total 844
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 553
telemt_desync_frames_bucket_total{bucket="gt_10"} 588
telemt_pool_swap_total 25
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 144
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4293
telemt_me_writer_restored_same_endpoint_total 4244
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 511296
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 6764646896 (6.30 GB)
telemt_user_octets_to_client{user="hello"} 116220687222 (108.24 GB)
telemt_user_msgs_from_client{user="hello"} 7943
telemt_user_msgs_to_client{user="hello"} 12935
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 32402.7 (9h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1829740
telemt_connections_bad_total 106286
telemt_connections_current 1685
telemt_connections_me_current 1685
telemt_handshake_timeouts_total 33090
telemt_upstream_connect_attempt_total 5351
telemt_upstream_connect_success_total 5311
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 5351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3716
telemt_me_reconnect_success_total 3682
telemt_me_reader_eof_total 3872
telemt_me_idle_close_by_peer_total 3872
telemt_me_route_drop_no_conn_total 686314
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1588420
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8498
telemt_desync_full_logged_total 2671
telemt_desync_suppressed_total 5827
telemt_desync_frames_bucket_total{bucket="1_2"} 1572
telemt_desync_frames_bucket_total{bucket="3_10"} 2970
telemt_desync_frames_bucket_total{bucket="gt_10"} 3956
telemt_pool_swap_total 30
telemt_me_writer_close_signal_drop_total 35
telemt_me_writer_removed_unexpected_total 3751
telemt_me_writer_restored_same_endpoint_total 3665
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1587570
telemt_user_connections_current{user="hello"} 1685
telemt_user_octets_from_client{user="hello"} 27028679924 (25.17 GB)
telemt_user_octets_to_client{user="hello"} 782882981448 (729.12 GB)
telemt_user_unique_ips_current{user="hello"} 605
telemt_user_unique_ips_recent_window{user="hello"} 135
```