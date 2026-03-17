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

# Server Metrics 2026-03-17 12:57:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 65510.8 (18h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 631185
telemt_connections_bad_total 5066
telemt_handshake_timeouts_total 19886
telemt_upstream_connect_attempt_total 16262
telemt_upstream_connect_success_total 15811
telemt_upstream_connect_fail_total 451
telemt_upstream_connect_attempts_per_request{bucket="1"} 16262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 451
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 13011
telemt_me_reconnect_success_total 10255
telemt_me_reader_eof_total 10895
telemt_me_idle_close_by_peer_total 10894
telemt_me_route_drop_no_conn_total 205246
telemt_me_route_drop_channel_closed_total 62
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 569929
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4248
telemt_desync_full_logged_total 1151
telemt_desync_suppressed_total 3097
telemt_desync_frames_bucket_total{bucket="1_2"} 1228
telemt_desync_frames_bucket_total{bucket="3_10"} 1761
telemt_desync_frames_bucket_total{bucket="gt_10"} 1259
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10490
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 10233
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 235
telemt_user_connections_total{user="hello"} 571815
telemt_user_connections_current{user="hello"} 942
telemt_user_octets_from_client{user="hello"} 7797156943 (7.26 GB)
telemt_user_octets_to_client{user="hello"} 203237100023 (189.28 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 65762.2 (18h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372154
telemt_connections_bad_total 21793
telemt_handshake_timeouts_total 20145
telemt_upstream_connect_attempt_total 16631
telemt_upstream_connect_success_total 16366
telemt_upstream_connect_fail_total 265
telemt_upstream_connect_attempts_per_request{bucket="1"} 16631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 327
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 265
telemt_me_keepalive_timeout_total 244
telemt_me_reconnect_attempts_total 25474
telemt_me_reconnect_success_total 13076
telemt_me_reader_eof_total 14051
telemt_me_idle_close_by_peer_total 14051
telemt_me_route_drop_no_conn_total 144300
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 310554
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1173
telemt_desync_full_logged_total 390
telemt_desync_suppressed_total 783
telemt_desync_frames_bucket_total{bucket="1_2"} 271
telemt_desync_frames_bucket_total{bucket="3_10"} 524
telemt_desync_frames_bucket_total{bucket="gt_10"} 378
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13621
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 13060
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 310531
telemt_user_connections_current{user="hello"} 632
telemt_user_octets_from_client{user="hello"} 3512517640 (3.27 GB)
telemt_user_octets_to_client{user="hello"} 111621887056 (103.96 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 65538.3 (18h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207413
telemt_connections_bad_total 7742
telemt_handshake_timeouts_total 16502
telemt_upstream_connect_attempt_total 17103
telemt_upstream_connect_success_total 17015
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 17103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9378
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 15599
telemt_me_reconnect_success_total 13722
telemt_me_reader_eof_total 14645
telemt_me_idle_close_by_peer_total 14645
telemt_me_route_drop_no_conn_total 69821
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172127
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 671
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 491
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 287
telemt_desync_frames_bucket_total{bucket="gt_10"} 127
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13975
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 13711
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 172020
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 15192395088 (14.15 GB)
telemt_user_octets_to_client{user="hello"} 48489930844 (45.16 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 65597.5 (18h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 474005
telemt_connections_bad_total 7735
telemt_handshake_timeouts_total 12515
telemt_upstream_connect_attempt_total 15794
telemt_upstream_connect_success_total 15652
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 15794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7770
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 14734
telemt_me_reconnect_success_total 11353
telemt_me_reader_eof_total 12118
telemt_me_idle_close_by_peer_total 12118
telemt_me_route_drop_no_conn_total 134211
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 399301
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1392
telemt_desync_full_logged_total 490
telemt_desync_suppressed_total 902
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 634
telemt_desync_frames_bucket_total{bucket="gt_10"} 419
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 11660
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 11344
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 307
telemt_user_connections_total{user="hello"} 400176
telemt_user_connections_current{user="hello"} 735
telemt_user_octets_from_client{user="hello"} 5172216730 (4.82 GB)
telemt_user_octets_to_client{user="hello"} 139382007851 (129.81 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 65569.5 (18h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238084
telemt_connections_bad_total 52947
telemt_handshake_timeouts_total 3160
telemt_upstream_connect_attempt_total 19117
telemt_upstream_connect_success_total 18872
telemt_upstream_connect_fail_total 245
telemt_upstream_connect_attempts_per_request{bucket="1"} 19117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 242
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 245
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 30135
telemt_me_reconnect_success_total 15480
telemt_me_reader_eof_total 16577
telemt_me_idle_close_by_peer_total 16577
telemt_me_route_drop_no_conn_total 63528
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173606
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1019
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 809
telemt_desync_frames_bucket_total{bucket="1_2"} 518
telemt_desync_frames_bucket_total{bucket="3_10"} 380
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 16142
telemt_me_refill_failed_total 455
telemt_me_writer_restored_same_endpoint_total 15472
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 662
telemt_user_connections_total{user="hello"} 173614
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 2307655427 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 68638630298 (63.92 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 65730.9 (18h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 566886
telemt_connections_bad_total 52093
telemt_handshake_timeouts_total 5423
telemt_upstream_connect_attempt_total 13187
telemt_upstream_connect_success_total 13116
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 13187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6605
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 36
telemt_me_reconnect_attempts_total 13750
telemt_me_reconnect_success_total 9852
telemt_me_reader_eof_total 10609
telemt_me_idle_close_by_peer_total 10609
telemt_me_route_drop_no_conn_total 364231
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 558825
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 831
telemt_desync_full_logged_total 305
telemt_desync_suppressed_total 526
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 318
telemt_desync_frames_bucket_total{bucket="gt_10"} 304
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10124
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9838
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 479242
telemt_user_connections_current{user="hello"} 962
telemt_user_octets_from_client{user="hello"} 7098972520 (6.61 GB)
telemt_user_octets_to_client{user="hello"} 229802026744 (214.02 GB)
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 13497.5 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10481
telemt_connections_bad_total 57
telemt_handshake_timeouts_total 42
telemt_upstream_connect_attempt_total 7458
telemt_upstream_connect_success_total 7394
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 7458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3471
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 9817
telemt_me_reconnect_success_total 6567
telemt_me_reader_eof_total 6856
telemt_me_idle_close_by_peer_total 6856
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 3793
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10091
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 10
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 6733
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 6555
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 10195
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 276177805 (263.38 MB)
telemt_user_octets_to_client{user="hello"} 20772546734 (19.35 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 9
```