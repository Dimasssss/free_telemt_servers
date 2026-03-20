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

# Server Metrics 2026-03-20 03:26:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 36525.7 (10h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 674223
telemt_connections_bad_total 46856
telemt_connections_current 887
telemt_connections_me_current 887
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 14948
telemt_upstream_connect_attempt_total 7455
telemt_upstream_connect_success_total 7363
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 7455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3191
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4464
telemt_me_reconnect_success_total 4424
telemt_me_reader_eof_total 4677
telemt_me_idle_close_by_peer_total 4676
telemt_me_route_drop_no_conn_total 191159
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 533719
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2506
telemt_desync_full_logged_total 915
telemt_desync_suppressed_total 1591
telemt_desync_frames_bucket_total{bucket="1_2"} 516
telemt_desync_frames_bucket_total{bucket="3_10"} 902
telemt_desync_frames_bucket_total{bucket="gt_10"} 1088
telemt_pool_swap_total 40
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4461
telemt_me_writer_restored_same_endpoint_total 4411
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 535043
telemt_user_connections_current{user="hello"} 887
telemt_user_octets_from_client{user="hello"} 31089890516 (28.95 GB)
telemt_user_octets_to_client{user="hello"} 182286747817 (169.77 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 372
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 52981.2 (14h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3216825
telemt_connections_bad_total 188120
telemt_connections_current 1987
telemt_connections_me_current 1987
telemt_handshake_timeouts_total 69872
telemt_upstream_connect_attempt_total 10302
telemt_upstream_connect_success_total 10121
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 10302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10517
telemt_me_reconnect_success_total 6268
telemt_me_reader_eof_total 6706
telemt_me_idle_close_by_peer_total 6706
telemt_me_route_drop_no_conn_total 1545910
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2716889
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11583
telemt_desync_full_logged_total 3828
telemt_desync_suppressed_total 7755
telemt_desync_frames_bucket_total{bucket="1_2"} 2219
telemt_desync_frames_bucket_total{bucket="3_10"} 4521
telemt_desync_frames_bucket_total{bucket="gt_10"} 4843
telemt_pool_swap_total 46
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6474
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6213
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 2716617
telemt_user_connections_current{user="hello"} 1987
telemt_user_octets_from_client{user="hello"} 41304267438 (38.47 GB)
telemt_user_octets_to_client{user="hello"} 1010946280886 (941.52 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 807
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 52959.3 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3081100
telemt_connections_bad_total 481552
telemt_connections_current 1697
telemt_connections_me_current 1697
telemt_handshake_timeouts_total 49142
telemt_upstream_connect_attempt_total 8637
telemt_upstream_connect_success_total 8576
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 8637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4220
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6889
telemt_me_reconnect_success_total 5953
telemt_me_reader_eof_total 6259
telemt_me_idle_close_by_peer_total 6258
telemt_me_route_drop_no_conn_total 1966482
telemt_me_route_drop_channel_closed_total 174
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2137308
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7986
telemt_desync_full_logged_total 2447
telemt_desync_suppressed_total 5539
telemt_desync_frames_bucket_total{bucket="1_2"} 1960
telemt_desync_frames_bucket_total{bucket="3_10"} 3032
telemt_desync_frames_bucket_total{bucket="gt_10"} 2994
telemt_pool_swap_total 52
telemt_me_writer_close_signal_drop_total 73
telemt_me_writer_removed_unexpected_total 6013
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5952
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 2132334
telemt_user_connections_current{user="hello"} 1697
telemt_user_octets_from_client{user="hello"} 32546711992 (30.31 GB)
telemt_user_octets_to_client{user="hello"} 831142396204 (774.06 GB)
telemt_user_unique_ips_current{user="hello"} 641
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 52947.2 (14h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2764690
telemt_connections_bad_total 211251
telemt_connections_current 1578
telemt_connections_me_current 1578
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 32934
telemt_upstream_connect_attempt_total 58595
telemt_upstream_connect_success_total 54182
telemt_upstream_connect_fail_total 4413
telemt_upstream_connect_attempts_per_request{bucket="1"} 58595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8127
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 548
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4413
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9234
telemt_me_reconnect_success_total 6325
telemt_me_reader_eof_total 6587
telemt_me_idle_close_by_peer_total 6586
telemt_me_route_drop_no_conn_total 1921715
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2237752
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8648
telemt_desync_full_logged_total 2759
telemt_desync_suppressed_total 5889
telemt_desync_frames_bucket_total{bucket="1_2"} 2128
telemt_desync_frames_bucket_total{bucket="3_10"} 3150
telemt_desync_frames_bucket_total{bucket="gt_10"} 3370
telemt_pool_swap_total 39
telemt_me_writer_close_signal_drop_total 540
telemt_me_writer_removed_unexpected_total 6995
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6321
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 670
telemt_user_connections_total{user="hello"} 2281396
telemt_user_connections_current{user="hello"} 1578
telemt_user_octets_from_client{user="hello"} 36626992160 (34.11 GB)
telemt_user_octets_to_client{user="hello"} 657780456101 (612.61 GB)
telemt_user_msgs_from_client{user="hello"} 245686
telemt_user_msgs_to_client{user="hello"} 1753278
telemt_user_unique_ips_current{user="hello"} 589
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 106670.1 (29h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6441150
telemt_connections_bad_total 1091337
telemt_connections_current 1822
telemt_connections_me_current 1822
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 115701
telemt_upstream_connect_attempt_total 128635
telemt_upstream_connect_success_total 95344
telemt_upstream_connect_fail_total 33291
telemt_upstream_connect_attempts_per_request{bucket="1"} 128635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33291
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79387
telemt_me_reconnect_success_total 13713
telemt_me_reader_eof_total 14760
telemt_me_idle_close_by_peer_total 14746
telemt_me_route_drop_no_conn_total 2835040
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4559330
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
telemt_desync_total 19895
telemt_desync_full_logged_total 6318
telemt_desync_suppressed_total 13577
telemt_desync_frames_bucket_total{bucket="1_2"} 3511
telemt_desync_frames_bucket_total{bucket="3_10"} 8225
telemt_desync_frames_bucket_total{bucket="gt_10"} 8159
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 14028
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13688
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 4634402
telemt_user_connections_current{user="hello"} 1822
telemt_user_octets_from_client{user="hello"} 73721174048 (68.66 GB)
telemt_user_octets_to_client{user="hello"} 1801526119040 (1.64 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 705
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 52910.2 (14h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1044633
telemt_connections_bad_total 94347
telemt_connections_current 576
telemt_connections_me_current 576
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13467
telemt_upstream_connect_attempt_total 13769
telemt_upstream_connect_success_total 13439
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 58
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 472920
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585597
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
telemt_desync_total 1421
telemt_desync_full_logged_total 543
telemt_desync_suppressed_total 878
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 599
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 882895
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 7875888647 (7.33 GB)
telemt_user_octets_to_client{user="hello"} 146599773170 (136.53 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 52911.6 (14h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2136059
telemt_connections_bad_total 125618
telemt_connections_current 1618
telemt_connections_me_current 1618
telemt_handshake_timeouts_total 39761
telemt_upstream_connect_attempt_total 9545
telemt_upstream_connect_success_total 9480
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9545
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4324
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6892
telemt_me_reconnect_success_total 6846
telemt_me_reader_eof_total 7229
telemt_me_idle_close_by_peer_total 7229
telemt_me_route_drop_no_conn_total 771315
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1819286
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9449
telemt_desync_full_logged_total 3050
telemt_desync_suppressed_total 6399
telemt_desync_frames_bucket_total{bucket="1_2"} 1815
telemt_desync_frames_bucket_total{bucket="3_10"} 3303
telemt_desync_frames_bucket_total{bucket="gt_10"} 4331
telemt_pool_swap_total 53
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6942
telemt_me_writer_restored_same_endpoint_total 6829
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 1818386
telemt_user_connections_current{user="hello"} 1618
telemt_user_octets_from_client{user="hello"} 30791695532 (28.68 GB)
telemt_user_octets_to_client{user="hello"} 933040002792 (868.96 GB)
telemt_user_unique_ips_current{user="hello"} 615
telemt_user_unique_ips_recent_window{user="hello"} 137
```