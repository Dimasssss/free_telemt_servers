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

# Server Metrics 2026-03-19 22:45:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 19687.6 (5h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 435795
telemt_connections_bad_total 27028
telemt_connections_current 821
telemt_connections_me_current 821
telemt_handshake_timeouts_total 6260
telemt_upstream_connect_attempt_total 3232
telemt_upstream_connect_success_total 3204
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 3232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 2232
telemt_me_reconnect_success_total 2215
telemt_me_reader_eof_total 2346
telemt_me_idle_close_by_peer_total 2346
telemt_me_route_drop_no_conn_total 129549
telemt_me_route_drop_channel_closed_total 51
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345078
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1851
telemt_desync_full_logged_total 652
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 382
telemt_desync_frames_bucket_total{bucket="3_10"} 601
telemt_desync_frames_bucket_total{bucket="gt_10"} 868
telemt_pool_swap_total 21
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 2262
telemt_me_writer_restored_same_endpoint_total 2202
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 345345
telemt_user_connections_current{user="hello"} 821
telemt_user_octets_from_client{user="hello"} 15841800508 (14.75 GB)
telemt_user_octets_to_client{user="hello"} 128638081932 (119.80 GB)
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 36142.9 (10h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2809533
telemt_connections_bad_total 120314
telemt_connections_current 1585
telemt_connections_me_current 1585
telemt_handshake_timeouts_total 56716
telemt_upstream_connect_attempt_total 7316
telemt_upstream_connect_success_total 7202
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 7316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2776
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8369
telemt_me_reconnect_success_total 4137
telemt_me_reader_eof_total 4444
telemt_me_idle_close_by_peer_total 4444
telemt_me_route_drop_no_conn_total 1450119
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2399949
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10612
telemt_desync_full_logged_total 3481
telemt_desync_suppressed_total 7131
telemt_desync_frames_bucket_total{bucket="1_2"} 1987
telemt_desync_frames_bucket_total{bucket="3_10"} 4149
telemt_desync_frames_bucket_total{bucket="gt_10"} 4476
telemt_pool_swap_total 29
telemt_me_writer_close_signal_drop_total 43
telemt_me_writer_removed_unexpected_total 4309
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4082
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 2399827
telemt_user_connections_current{user="hello"} 1585
telemt_user_octets_from_client{user="hello"} 37760809670 (35.17 GB)
telemt_user_octets_to_client{user="hello"} 862510787926 (803.28 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 694
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 36121.0 (10h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2734782
telemt_connections_bad_total 461670
telemt_connections_current 1298
telemt_connections_me_current 1298
telemt_handshake_timeouts_total 35524
telemt_upstream_connect_attempt_total 5675
telemt_upstream_connect_success_total 5629
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 5675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2722
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4720
telemt_me_reconnect_success_total 3789
telemt_me_reader_eof_total 3949
telemt_me_idle_close_by_peer_total 3948
telemt_me_route_drop_no_conn_total 1871575
telemt_me_route_drop_channel_closed_total 168
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1906748
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7412
telemt_desync_full_logged_total 2244
telemt_desync_suppressed_total 5168
telemt_desync_frames_bucket_total{bucket="1_2"} 1824
telemt_desync_frames_bucket_total{bucket="3_10"} 2834
telemt_desync_frames_bucket_total{bucket="gt_10"} 2754
telemt_pool_swap_total 34
telemt_me_writer_close_signal_drop_total 62
telemt_me_writer_removed_unexpected_total 3821
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3788
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 1902569
telemt_user_connections_current{user="hello"} 1298
telemt_user_octets_from_client{user="hello"} 28710113816 (26.74 GB)
telemt_user_octets_to_client{user="hello"} 712475805076 (663.54 GB)
telemt_user_unique_ips_current{user="hello"} 521
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 36108.9 (10h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2388413
telemt_connections_bad_total 99838
telemt_connections_current 1235
telemt_connections_me_current 1235
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 29606
telemt_upstream_connect_attempt_total 36041
telemt_upstream_connect_success_total 34284
telemt_upstream_connect_fail_total 1757
telemt_upstream_connect_attempts_per_request{bucket="1"} 36041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5718
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 457
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1757
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7005
telemt_me_reconnect_success_total 4368
telemt_me_reader_eof_total 4532
telemt_me_idle_close_by_peer_total 4531
telemt_me_route_drop_no_conn_total 1832982
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2028270
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8116
telemt_desync_full_logged_total 2559
telemt_desync_suppressed_total 5557
telemt_desync_frames_bucket_total{bucket="1_2"} 1988
telemt_desync_frames_bucket_total{bucket="3_10"} 2948
telemt_desync_frames_bucket_total{bucket="gt_10"} 3180
telemt_pool_swap_total 21
telemt_me_writer_close_signal_drop_total 349
telemt_me_writer_removed_unexpected_total 4895
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 4364
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 527
telemt_user_connections_total{user="hello"} 2055201
telemt_user_connections_current{user="hello"} 1235
telemt_user_octets_from_client{user="hello"} 33625107168 (31.32 GB)
telemt_user_octets_to_client{user="hello"} 538599784251 (501.61 GB)
telemt_user_msgs_from_client{user="hello"} 69950
telemt_user_msgs_to_client{user="hello"} 147135
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 89832.1 (24h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6065987
telemt_connections_bad_total 1036688
telemt_connections_current 1479
telemt_connections_me_current 1479
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 109707
telemt_upstream_connect_attempt_total 67296
telemt_upstream_connect_success_total 64788
telemt_upstream_connect_fail_total 2508
telemt_upstream_connect_attempts_per_request{bucket="1"} 67296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9601
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1058
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2508
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 76559
telemt_me_reconnect_success_total 11140
telemt_me_reader_eof_total 11763
telemt_me_idle_close_by_peer_total 11760
telemt_me_route_drop_no_conn_total 2758695
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4314839
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
telemt_desync_total 18998
telemt_desync_full_logged_total 5913
telemt_desync_suppressed_total 13085
telemt_desync_frames_bucket_total{bucket="1_2"} 3317
telemt_desync_frames_bucket_total{bucket="3_10"} 7802
telemt_desync_frames_bucket_total{bucket="gt_10"} 7879
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 11408
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 11116
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 4362888
telemt_user_connections_current{user="hello"} 1479
telemt_user_octets_from_client{user="hello"} 67635671743 (62.99 GB)
telemt_user_octets_to_client{user="hello"} 1694763805260 (1.54 TB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 606
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 36072.1 (10h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 641436
telemt_connections_bad_total 50471
telemt_connections_current 373
telemt_connections_me_current 373
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12426
telemt_upstream_connect_attempt_total 10165
telemt_upstream_connect_success_total 9924
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 10165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5553
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 591
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 4869
telemt_me_reconnect_success_total 4783
telemt_me_reader_eof_total 4990
telemt_me_idle_close_by_peer_total 4988
telemt_me_route_drop_no_conn_total 450418
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 543830
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
telemt_desync_total 1362
telemt_desync_full_logged_total 508
telemt_desync_suppressed_total 854
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 558
telemt_desync_frames_bucket_total{bucket="gt_10"} 589
telemt_pool_swap_total 29
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 147
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 4828
telemt_me_writer_restored_same_endpoint_total 4774
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 530818
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 6973420329 (6.49 GB)
telemt_user_octets_to_client{user="hello"} 127884104852 (119.10 GB)
telemt_user_msgs_from_client{user="hello"} 8558
telemt_user_msgs_to_client{user="hello"} 13690
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 36073.5 (10h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1897493
telemt_connections_bad_total 112567
telemt_connections_current 1278
telemt_connections_me_current 1278
telemt_handshake_timeouts_total 35448
telemt_upstream_connect_attempt_total 6119
telemt_upstream_connect_success_total 6073
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 6119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4279
telemt_me_reconnect_success_total 4244
telemt_me_reader_eof_total 4466
telemt_me_idle_close_by_peer_total 4466
telemt_me_route_drop_no_conn_total 707051
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1639511
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8776
telemt_desync_full_logged_total 2782
telemt_desync_suppressed_total 5994
telemt_desync_frames_bucket_total{bucket="1_2"} 1609
telemt_desync_frames_bucket_total{bucket="3_10"} 3074
telemt_desync_frames_bucket_total{bucket="gt_10"} 4093
telemt_pool_swap_total 34
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 4318
telemt_me_writer_restored_same_endpoint_total 4227
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 1638649
telemt_user_connections_current{user="hello"} 1278
telemt_user_octets_from_client{user="hello"} 27929072408 (26.01 GB)
telemt_user_octets_to_client{user="hello"} 825025615460 (768.36 GB)
telemt_user_unique_ips_current{user="hello"} 518
telemt_user_unique_ips_recent_window{user="hello"} 98
```