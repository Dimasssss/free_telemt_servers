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

# Server Metrics 2026-03-19 23:06:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 20910.3 (5h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449042
telemt_connections_bad_total 28351
telemt_connections_current 793
telemt_connections_me_current 793
telemt_handshake_timeouts_total 6622
telemt_upstream_connect_attempt_total 3488
telemt_upstream_connect_success_total 3457
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 3487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1762
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 2400
telemt_me_reconnect_success_total 2382
telemt_me_reader_eof_total 2529
telemt_me_idle_close_by_peer_total 2529
telemt_me_route_drop_no_conn_total 133027
telemt_me_route_drop_channel_closed_total 51
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 355821
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1907
telemt_desync_full_logged_total 671
telemt_desync_suppressed_total 1236
telemt_desync_frames_bucket_total{bucket="1_2"} 393
telemt_desync_frames_bucket_total{bucket="3_10"} 624
telemt_desync_frames_bucket_total{bucket="gt_10"} 890
telemt_pool_swap_total 23
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 2432
telemt_me_writer_restored_same_endpoint_total 2369
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 356094
telemt_user_connections_current{user="hello"} 793
telemt_user_octets_from_client{user="hello"} 19720861380 (18.37 GB)
telemt_user_octets_to_client{user="hello"} 131774483596 (122.72 GB)
telemt_user_unique_ips_current{user="hello"} 292
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 37365.8 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2840397
telemt_connections_bad_total 122447
telemt_connections_current 1597
telemt_connections_me_current 1597
telemt_handshake_timeouts_total 57864
telemt_upstream_connect_attempt_total 7512
telemt_upstream_connect_success_total 7392
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 7512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8518
telemt_me_reconnect_success_total 4283
telemt_me_reader_eof_total 4596
telemt_me_idle_close_by_peer_total 4596
telemt_me_route_drop_no_conn_total 1457623
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2426400
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10688
telemt_desync_full_logged_total 3513
telemt_desync_suppressed_total 7175
telemt_desync_frames_bucket_total{bucket="1_2"} 2004
telemt_desync_frames_bucket_total{bucket="3_10"} 4185
telemt_desync_frames_bucket_total{bucket="gt_10"} 4499
telemt_pool_swap_total 30
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 4461
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4228
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 2426276
telemt_user_connections_current{user="hello"} 1597
telemt_user_octets_from_client{user="hello"} 38078185006 (35.46 GB)
telemt_user_octets_to_client{user="hello"} 874352804350 (814.30 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 679
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 37344.1 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2761880
telemt_connections_bad_total 462824
telemt_connections_current 1181
telemt_connections_me_current 1181
telemt_handshake_timeouts_total 36303
telemt_upstream_connect_attempt_total 5888
telemt_upstream_connect_success_total 5841
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 5888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2838
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4889
telemt_me_reconnect_success_total 3959
telemt_me_reader_eof_total 4128
telemt_me_idle_close_by_peer_total 4127
telemt_me_route_drop_no_conn_total 1878480
telemt_me_route_drop_channel_closed_total 169
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1924509
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7458
telemt_desync_full_logged_total 2257
telemt_desync_suppressed_total 5201
telemt_desync_frames_bucket_total{bucket="1_2"} 1828
telemt_desync_frames_bucket_total{bucket="3_10"} 2847
telemt_desync_frames_bucket_total{bucket="gt_10"} 2783
telemt_pool_swap_total 35
telemt_me_writer_close_signal_drop_total 64
telemt_me_writer_removed_unexpected_total 3991
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3958
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 1920310
telemt_user_connections_current{user="hello"} 1181
telemt_user_octets_from_client{user="hello"} 28916172336 (26.93 GB)
telemt_user_octets_to_client{user="hello"} 724133196604 (674.40 GB)
telemt_user_unique_ips_current{user="hello"} 516
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 37331.8 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2409590
telemt_connections_bad_total 100187
telemt_connections_current 1110
telemt_connections_direct_current 1110
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_demotions_total 474
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 29755
telemt_upstream_connect_attempt_total 43652
telemt_upstream_connect_success_total 39824
telemt_upstream_connect_fail_total 3826
telemt_upstream_connect_attempts_per_request{bucket="1"} 43650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6140
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 498
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3826
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7245
telemt_me_reconnect_success_total 4504
telemt_me_reader_eof_total 4665
telemt_me_idle_close_by_peer_total 4664
telemt_me_route_drop_no_conn_total 1837429
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2039857
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8141
telemt_desync_full_logged_total 2567
telemt_desync_suppressed_total 5574
telemt_desync_frames_bucket_total{bucket="1_2"} 1993
telemt_desync_frames_bucket_total{bucket="3_10"} 2961
telemt_desync_frames_bucket_total{bucket="gt_10"} 3187
telemt_pool_swap_total 23
telemt_me_writer_close_signal_drop_total 403
telemt_me_writer_removed_unexpected_total 5065
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 4500
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 2072134
telemt_user_connections_current{user="hello"} 1110
telemt_user_octets_from_client{user="hello"} 33901588844 (31.57 GB)
telemt_user_octets_to_client{user="hello"} 549384281356 (511.65 GB)
telemt_user_msgs_from_client{user="hello"} 112796
telemt_user_msgs_to_client{user="hello"} 500037
telemt_user_unique_ips_current{user="hello"} 395
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 91055.2 (25h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6114245
telemt_connections_bad_total 1036923
telemt_connections_current 933
telemt_connections_direct_current 933
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1983
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 110148
telemt_upstream_connect_attempt_total 99071
telemt_upstream_connect_success_total 67748
telemt_upstream_connect_fail_total 31322
telemt_upstream_connect_attempts_per_request{bucket="1"} 99070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1322
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31322
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 76860
telemt_me_reconnect_success_total 11324
telemt_me_reader_eof_total 12085
telemt_me_idle_close_by_peer_total 12074
telemt_me_route_drop_no_conn_total 2763367
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4329828
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
telemt_desync_total 19068
telemt_desync_full_logged_total 5962
telemt_desync_suppressed_total 13106
telemt_desync_frames_bucket_total{bucket="1_2"} 3332
telemt_desync_frames_bucket_total{bucket="3_10"} 7824
telemt_desync_frames_bucket_total{bucket="gt_10"} 7912
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 11609
telemt_me_refill_failed_total 2043
telemt_me_writer_restored_same_endpoint_total 11299
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 4380590
telemt_user_connections_current{user="hello"} 933
telemt_user_octets_from_client{user="hello"} 67811793593 (63.15 GB)
telemt_user_octets_to_client{user="hello"} 1702432839668 (1.55 TB)
telemt_user_msgs_from_client{user="hello"} 565505
telemt_user_msgs_to_client{user="hello"} 1933102
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 37295.0 (10h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 647866
telemt_connections_bad_total 51464
telemt_connections_current 319
telemt_connections_me_current 319
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12781
telemt_upstream_connect_attempt_total 10448
telemt_upstream_connect_success_total 10205
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 10448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3724
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5708
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 593
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 5091
telemt_me_reconnect_success_total 5001
telemt_me_reader_eof_total 5225
telemt_me_idle_close_by_peer_total 5223
telemt_me_route_drop_no_conn_total 452768
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 548369
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
telemt_desync_total 1379
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 866
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 566
telemt_desync_frames_bucket_total{bucket="gt_10"} 596
telemt_pool_swap_total 31
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 148
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 5049
telemt_me_writer_restored_same_endpoint_total 4992
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1178
telemt_me_async_recovery_trigger_total 1239
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 535357
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 7036274853 (6.55 GB)
telemt_user_octets_to_client{user="hello"} 129565849108 (120.67 GB)
telemt_user_msgs_from_client{user="hello"} 8558
telemt_user_msgs_to_client{user="hello"} 13690
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 37296.4 (10h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1916629
telemt_connections_bad_total 116053
telemt_connections_current 1257
telemt_connections_me_current 1257
telemt_handshake_timeouts_total 35627
telemt_upstream_connect_attempt_total 6377
telemt_upstream_connect_success_total 6329
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 6377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2908
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4476
telemt_me_reconnect_success_total 4440
telemt_me_reader_eof_total 4682
telemt_me_idle_close_by_peer_total 4682
telemt_me_route_drop_no_conn_total 712371
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1654072
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8814
telemt_desync_full_logged_total 2802
telemt_desync_suppressed_total 6012
telemt_desync_frames_bucket_total{bucket="1_2"} 1613
telemt_desync_frames_bucket_total{bucket="3_10"} 3090
telemt_desync_frames_bucket_total{bucket="gt_10"} 4111
telemt_pool_swap_total 36
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 4516
telemt_me_writer_restored_same_endpoint_total 4423
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 1653209
telemt_user_connections_current{user="hello"} 1257
telemt_user_octets_from_client{user="hello"} 28084940620 (26.16 GB)
telemt_user_octets_to_client{user="hello"} 834646271648 (777.32 GB)
telemt_user_unique_ips_current{user="hello"} 514
telemt_user_unique_ips_recent_window{user="hello"} 105
```