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

# Server Metrics 2026-03-19 09:27:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 41963.8 (11h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 862084
telemt_connections_bad_total 80545
telemt_connections_current 1627
telemt_connections_me_current 1627
telemt_handshake_timeouts_total 33519
telemt_upstream_connect_attempt_total 7987
telemt_upstream_connect_success_total 7848
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 7987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4044
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 6903
telemt_me_reconnect_success_total 5747
telemt_me_reader_eof_total 6094
telemt_me_idle_close_by_peer_total 6093
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 294139
telemt_me_route_drop_channel_closed_total 113
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 671785
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4146
telemt_desync_full_logged_total 1243
telemt_desync_suppressed_total 2903
telemt_desync_frames_bucket_total{bucket="1_2"} 1383
telemt_desync_frames_bucket_total{bucket="3_10"} 1522
telemt_desync_frames_bucket_total{bucket="gt_10"} 1241
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5852
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5728
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 666209
telemt_user_connections_current{user="hello"} 1627
telemt_user_octets_from_client{user="hello"} 10479605900 (9.76 GB)
telemt_user_octets_to_client{user="hello"} 216481505528 (201.61 GB)
telemt_user_unique_ips_current{user="hello"} 569
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 41968.7 (11h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2126128
telemt_connections_bad_total 113231
telemt_connections_current 4295
telemt_connections_me_current 4295
telemt_handshake_timeouts_total 47246
telemt_upstream_connect_attempt_total 7996
telemt_upstream_connect_success_total 7847
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 7996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 8071
telemt_me_reconnect_success_total 5726
telemt_me_reader_eof_total 6096
telemt_me_idle_close_by_peer_total 6096
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 948861
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1772130
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7904
telemt_desync_full_logged_total 2662
telemt_desync_suppressed_total 5242
telemt_desync_frames_bucket_total{bucket="1_2"} 1436
telemt_desync_frames_bucket_total{bucket="3_10"} 3054
telemt_desync_frames_bucket_total{bucket="gt_10"} 3414
telemt_pool_swap_total 32
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5899
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 5704
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 1771896
telemt_user_connections_current{user="hello"} 4295
telemt_user_octets_from_client{user="hello"} 28814360144 (26.84 GB)
telemt_user_octets_to_client{user="hello"} 657410884348 (612.26 GB)
telemt_user_unique_ips_current{user="hello"} 1444
telemt_user_unique_ips_recent_window{user="hello"} 647
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 41965.9 (11h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1808448
telemt_connections_bad_total 216993
telemt_connections_current 3032
telemt_connections_me_current 3032
telemt_handshake_timeouts_total 44633
telemt_upstream_connect_attempt_total 7488
telemt_upstream_connect_success_total 7488
telemt_upstream_connect_attempts_per_request{bucket="1"} 7488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3548
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 5401
telemt_me_reconnect_success_total 5368
telemt_me_reader_eof_total 5683
telemt_me_idle_close_by_peer_total 5683
telemt_me_route_drop_no_conn_total 847352
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1406355
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6373
telemt_desync_full_logged_total 1987
telemt_desync_suppressed_total 4386
telemt_desync_frames_bucket_total{bucket="1_2"} 1449
telemt_desync_frames_bucket_total{bucket="3_10"} 2299
telemt_desync_frames_bucket_total{bucket="gt_10"} 2625
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 5463
telemt_me_writer_restored_same_endpoint_total 5352
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 1405001
telemt_user_connections_current{user="hello"} 3032
telemt_user_octets_from_client{user="hello"} 21909492084 (20.40 GB)
telemt_user_octets_to_client{user="hello"} 651865592856 (607.10 GB)
telemt_user_unique_ips_current{user="hello"} 1045
telemt_user_unique_ips_recent_window{user="hello"} 492
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 42019.0 (11h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1881193
telemt_connections_bad_total 101292
telemt_connections_current 3052
telemt_connections_me_current 3052
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 47654
telemt_upstream_connect_attempt_total 15691
telemt_upstream_connect_success_total 15579
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 15691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4315
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7712
telemt_me_reconnect_success_total 5302
telemt_me_reader_eof_total 5638
telemt_me_idle_close_by_peer_total 5637
telemt_me_route_drop_no_conn_total 945796
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1401087
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5081
telemt_desync_full_logged_total 1725
telemt_desync_suppressed_total 3356
telemt_desync_frames_bucket_total{bucket="1_2"} 1041
telemt_desync_frames_bucket_total{bucket="3_10"} 1985
telemt_desync_frames_bucket_total{bucket="gt_10"} 2055
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 5571
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 5278
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 1407756
telemt_user_connections_current{user="hello"} 3052
telemt_user_octets_from_client{user="hello"} 16778800032 (15.63 GB)
telemt_user_octets_to_client{user="hello"} 409940042222 (381.79 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 975
telemt_user_unique_ips_recent_window{user="hello"} 454
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 41962.3 (11h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2179017
telemt_connections_bad_total 529657
telemt_connections_current 3467
telemt_connections_me_current 3467
telemt_handshake_timeouts_total 46244
telemt_upstream_connect_attempt_total 7263
telemt_upstream_connect_success_total 7212
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 7263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3509
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 5145
telemt_me_reconnect_success_total 5103
telemt_me_reader_eof_total 5409
telemt_me_idle_close_by_peer_total 5409
telemt_me_route_drop_no_conn_total 621617
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1389315
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6464
telemt_desync_full_logged_total 2015
telemt_desync_suppressed_total 4449
telemt_desync_frames_bucket_total{bucket="1_2"} 1295
telemt_desync_frames_bucket_total{bucket="3_10"} 2848
telemt_desync_frames_bucket_total{bucket="gt_10"} 2321
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 5176
telemt_me_writer_restored_same_endpoint_total 5079
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 1388524
telemt_user_connections_current{user="hello"} 3467
telemt_user_octets_from_client{user="hello"} 26189251704 (24.39 GB)
telemt_user_octets_to_client{user="hello"} 616782448020 (574.42 GB)
telemt_user_unique_ips_current{user="hello"} 1210
telemt_user_unique_ips_recent_window{user="hello"} 545
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 41974.2 (11h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 386885
telemt_connections_bad_total 17635
telemt_connections_current 920
telemt_connections_me_current 920
telemt_handshake_timeouts_total 3155
telemt_upstream_connect_attempt_total 10666
telemt_upstream_connect_success_total 10395
telemt_upstream_connect_fail_total 271
telemt_upstream_connect_attempts_per_request{bucket="1"} 10666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5217
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 271
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 13666
telemt_me_reconnect_success_total 8282
telemt_me_reader_eof_total 8782
telemt_me_idle_close_by_peer_total 8782
telemt_me_route_drop_no_conn_total 198178
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 346426
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 549
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 147
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 20
telemt_pool_stale_pick_total 193
telemt_me_writer_removed_unexpected_total 8516
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 8252
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 346389
telemt_user_connections_current{user="hello"} 920
telemt_user_octets_from_client{user="hello"} 4973593668 (4.63 GB)
telemt_user_octets_to_client{user="hello"} 140383383156 (130.74 GB)
telemt_user_unique_ips_current{user="hello"} 332
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 41964.8 (11h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1472246
telemt_connections_bad_total 129563
telemt_connections_current 3102
telemt_connections_me_current 3102
telemt_handshake_timeouts_total 64156
telemt_upstream_connect_attempt_total 8526
telemt_upstream_connect_success_total 8525
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 7753
telemt_me_reconnect_success_total 6404
telemt_me_reader_eof_total 6786
telemt_me_idle_close_by_peer_total 6785
telemt_me_route_drop_no_conn_total 579546
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1223507
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6984
telemt_desync_full_logged_total 2295
telemt_desync_suppressed_total 4689
telemt_desync_frames_bucket_total{bucket="1_2"} 1324
telemt_desync_frames_bucket_total{bucket="3_10"} 2625
telemt_desync_frames_bucket_total{bucket="gt_10"} 3035
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6521
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6389
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 117
telemt_user_connections_total{user="hello"} 1222387
telemt_user_connections_current{user="hello"} 3103
telemt_user_octets_from_client{user="hello"} 16827658940 (15.67 GB)
telemt_user_octets_to_client{user="hello"} 598421350312 (557.32 GB)
telemt_user_unique_ips_current{user="hello"} 1033
telemt_user_unique_ips_recent_window{user="hello"} 438
```