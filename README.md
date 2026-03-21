# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-21 23:47:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 9684.3 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152665
telemt_connections_bad_total 11252
telemt_connections_current 694
telemt_connections_me_current 694
telemt_handshake_timeouts_total 7680
telemt_upstream_connect_attempt_total 3892
telemt_upstream_connect_success_total 3891
telemt_upstream_connect_attempts_per_request{bucket="1"} 3891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2432
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 97
telemt_me_reconnect_success_total 63
telemt_me_reader_eof_total 64
telemt_me_idle_close_by_peer_total 64
telemt_me_route_drop_no_conn_total 32306
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124818
telemt_me_endpoint_quarantine_total 59
telemt_me_single_endpoint_shadow_rotate_total 83
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 737
telemt_desync_full_logged_total 234
telemt_desync_suppressed_total 503
telemt_desync_frames_bucket_total{bucket="1_2"} 142
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 355
telemt_pool_swap_total 10
telemt_pool_force_close_total 278
telemt_me_writer_close_signal_drop_total 19
telemt_me_draining_writers_reap_progress_total 3460
telemt_me_writer_removed_unexpected_total 60
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 258
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3250
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3182
telemt_me_writer_teardown_success_total{mode="normal"} 3508
telemt_me_writer_teardown_noop_total 3460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 6873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6968
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.183961
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6968
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 19
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 58
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 124668
telemt_user_connections_current{user="hello"} 694
telemt_user_octets_from_client{user="hello"} 1514725216 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 45986372840 (42.83 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 23050.4 (6h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 664818
telemt_connections_bad_total 33673
telemt_connections_current 435
telemt_connections_me_current 435
telemt_handshake_timeouts_total 25361
telemt_upstream_connect_attempt_total 9747
telemt_upstream_connect_success_total 9574
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 9729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5231
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_reconnect_attempts_total 831
telemt_me_reconnect_success_total 292
telemt_me_reader_eof_total 252
telemt_me_idle_close_by_peer_total 252
telemt_me_route_drop_no_conn_total 325343
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 540420
telemt_me_endpoint_quarantine_total 204
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 187
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 2378
telemt_desync_full_logged_total 1362
telemt_desync_suppressed_total 1016
telemt_desync_frames_bucket_total{bucket="1_2"} 505
telemt_desync_frames_bucket_total{bucket="3_10"} 892
telemt_desync_frames_bucket_total{bucket="gt_10"} 981
telemt_pool_swap_total 25
telemt_pool_force_close_total 703
telemt_me_writer_close_signal_drop_total 54
telemt_me_draining_writers_reap_progress_total 8590
telemt_me_writer_removed_unexpected_total 236
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 755
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8074
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 696
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7887
telemt_me_writer_teardown_success_total{mode="normal"} 8829
telemt_me_writer_teardown_noop_total 8590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 17419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17419
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.370027
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17419
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 54
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 202
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 539677
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 9034815944 (8.41 GB)
telemt_user_octets_to_client{user="hello"} 187121641692 (174.27 GB)
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 97910.2 (27h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7427913
telemt_connections_bad_total 588345
telemt_connections_current 1798
telemt_connections_me_current 1798
telemt_handshake_timeouts_total 240990
telemt_upstream_connect_attempt_total 35463
telemt_upstream_connect_success_total 35394
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 35401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1488
telemt_me_reconnect_success_total 741
telemt_me_reader_eof_total 749
telemt_me_idle_close_by_peer_total 749
telemt_me_route_drop_no_conn_total 4495830
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6057246
telemt_me_endpoint_quarantine_total 613
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 728
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 25716
telemt_desync_full_logged_total 8492
telemt_desync_suppressed_total 17224
telemt_desync_frames_bucket_total{bucket="1_2"} 5508
telemt_desync_frames_bucket_total{bucket="3_10"} 10044
telemt_desync_frames_bucket_total{bucket="gt_10"} 10164
telemt_pool_swap_total 105
telemt_pool_force_close_total 3533
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 568
telemt_me_draining_writers_reap_progress_total 32311
telemt_me_writer_removed_unexpected_total 721
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2743
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29866
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3294
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28778
telemt_me_writer_teardown_success_total{mode="normal"} 32609
telemt_me_writer_teardown_noop_total 32355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64964
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 152.434586
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64964
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 568
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 661
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 6049707
telemt_user_connections_current{user="hello"} 1798
telemt_user_octets_from_client{user="hello"} 103789228376 (96.66 GB)
telemt_user_octets_to_client{user="hello"} 1984137480716 (1.80 TB)
telemt_user_unique_ips_current{user="hello"} 829
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 97911.7 (27h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6106599
telemt_connections_bad_total 577493
telemt_connections_current 1606
telemt_connections_me_current 1606
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 201829
telemt_upstream_connect_attempt_total 39381
telemt_upstream_connect_success_total 39042
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 39221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18892
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1804
telemt_me_reconnect_success_total 768
telemt_me_reader_eof_total 746
telemt_me_idle_close_by_peer_total 746
telemt_me_route_drop_no_conn_total 2165838
telemt_me_route_drop_channel_closed_total 253
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4573106
telemt_me_endpoint_quarantine_total 597
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 748
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 22010
telemt_desync_full_logged_total 7442
telemt_desync_suppressed_total 14568
telemt_desync_frames_bucket_total{bucket="1_2"} 5300
telemt_desync_frames_bucket_total{bucket="3_10"} 8543
telemt_desync_frames_bucket_total{bucket="gt_10"} 8167
telemt_pool_swap_total 107
telemt_pool_force_close_total 3224
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 30854
telemt_me_writer_removed_unexpected_total 720
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2625
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28884
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3025
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27630
telemt_me_writer_teardown_success_total{mode="normal"} 31509
telemt_me_writer_teardown_noop_total 30860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62369
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.979382
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62369
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 664
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 4515933
telemt_user_connections_current{user="hello"} 1606
telemt_user_octets_from_client{user="hello"} 137811600653 (128.35 GB)
telemt_user_octets_to_client{user="hello"} 2111937193123 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 757
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 97875.6 (27h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6018765
telemt_connections_bad_total 539718
telemt_connections_current 1515
telemt_connections_me_current 1515
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 192286
telemt_upstream_connect_attempt_total 45866
telemt_upstream_connect_success_total 45558
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 45693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20357
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1805
telemt_me_reconnect_success_total 818
telemt_me_reader_eof_total 767
telemt_me_idle_close_by_peer_total 767
telemt_me_route_drop_no_conn_total 2101266
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4495759
telemt_me_endpoint_quarantine_total 660
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 732
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 21866
telemt_desync_full_logged_total 7273
telemt_desync_suppressed_total 14593
telemt_desync_frames_bucket_total{bucket="1_2"} 5350
telemt_desync_frames_bucket_total{bucket="3_10"} 8369
telemt_desync_frames_bucket_total{bucket="gt_10"} 8147
telemt_pool_swap_total 105
telemt_pool_force_close_total 3096
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 369
telemt_me_draining_writers_reap_progress_total 32356
telemt_me_writer_removed_unexpected_total 732
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2710
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30387
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2881
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29260
telemt_me_writer_teardown_success_total{mode="normal"} 33097
telemt_me_writer_teardown_noop_total 32367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65464
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.454183
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65464
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 369
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 708
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4497098
telemt_user_connections_current{user="hello"} 1515
telemt_user_octets_from_client{user="hello"} 131474744367 (122.45 GB)
telemt_user_octets_to_client{user="hello"} 2059647942159 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 742
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 97915.0 (27h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19943908
telemt_connections_bad_total 1464440
telemt_connections_current 2191
telemt_connections_me_current 2191
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 576320
telemt_upstream_connect_attempt_total 188964
telemt_upstream_connect_success_total 171353
telemt_upstream_connect_fail_total 16031
telemt_upstream_connect_attempts_per_request{bucket="1"} 187384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39914
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8881
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16031
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64336
telemt_me_reconnect_success_total 2146
telemt_me_reader_eof_total 1341
telemt_me_idle_close_by_peer_total 1340
telemt_me_route_drop_no_conn_total 39443888
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16242116
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 750
telemt_me_single_endpoint_outage_enter_total 122
telemt_me_single_endpoint_outage_exit_total 122
telemt_me_single_endpoint_outage_reconnect_attempt_total 258
telemt_me_single_endpoint_outage_reconnect_success_total 61
telemt_me_single_endpoint_quarantine_bypass_total 258
telemt_me_single_endpoint_shadow_rotate_total 763
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 31272
telemt_desync_full_logged_total 9295
telemt_desync_suppressed_total 21977
telemt_desync_frames_bucket_total{bucket="1_2"} 6821
telemt_desync_frames_bucket_total{bucket="3_10"} 13842
telemt_desync_frames_bucket_total{bucket="gt_10"} 10609
telemt_pool_swap_total 100
telemt_pool_force_close_total 3316
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 756
telemt_me_draining_writers_reap_progress_total 30363
telemt_me_writer_removed_unexpected_total 2001
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4185
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27914
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 516
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27047
telemt_me_writer_teardown_success_total{mode="normal"} 32099
telemt_me_writer_teardown_noop_total 30389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62488
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 211.170652
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62488
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 756
telemt_me_refill_failed_total 3789
telemt_me_writer_restored_same_endpoint_total 1484
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14672
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 16370083
telemt_user_connections_current{user="hello"} 2191
telemt_user_octets_from_client{user="hello"} 184924875516 (172.22 GB)
telemt_user_octets_to_client{user="hello"} 1107791932314 (1.01 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 996
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 97882.5 (27h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5817079
telemt_connections_bad_total 547839
telemt_connections_current 1429
telemt_connections_me_current 1429
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 119735
telemt_upstream_connect_attempt_total 53963
telemt_upstream_connect_success_total 53348
telemt_upstream_connect_fail_total 525
telemt_upstream_connect_attempts_per_request{bucket="1"} 53873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21245
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 339
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 525
telemt_me_reconnect_attempts_total 68085
telemt_me_reconnect_success_total 1679
telemt_me_reader_eof_total 1458
telemt_me_idle_close_by_peer_total 1457
telemt_me_route_drop_no_conn_total 2353877
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4533806
telemt_me_endpoint_quarantine_total 646
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 732
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 22927
telemt_desync_full_logged_total 8019
telemt_desync_suppressed_total 14908
telemt_desync_frames_bucket_total{bucket="1_2"} 4346
telemt_desync_frames_bucket_total{bucket="3_10"} 8884
telemt_desync_frames_bucket_total{bucket="gt_10"} 9697
telemt_pool_swap_total 100
telemt_pool_force_close_total 2946
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 33687
telemt_me_writer_removed_unexpected_total 1504
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3590
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31624
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2545
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30741
telemt_me_writer_teardown_success_total{mode="normal"} 35214
telemt_me_writer_teardown_noop_total 33688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68902
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.921425
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68902
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 4118
telemt_me_writer_restored_same_endpoint_total 1423
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 4526912
telemt_user_connections_current{user="hello"} 1429
telemt_user_octets_from_client{user="hello"} 121721099628 (113.36 GB)
telemt_user_octets_to_client{user="hello"} 1849593963134 (1.68 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 709
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 34718.3 (9h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3689307
telemt_connections_bad_total 130312
telemt_connections_current 1296
telemt_connections_me_current 1296
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1538322
telemt_upstream_connect_attempt_total 22188
telemt_upstream_connect_success_total 22048
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 22181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7149
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_reconnect_attempts_total 45583
telemt_me_reconnect_success_total 882
telemt_me_reader_eof_total 555
telemt_me_idle_close_by_peer_total 555
telemt_me_route_drop_no_conn_total 992489
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1780921
telemt_me_endpoint_quarantine_total 243
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 261
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 9894
telemt_desync_full_logged_total 3384
telemt_desync_suppressed_total 6510
telemt_desync_frames_bucket_total{bucket="1_2"} 1753
telemt_desync_frames_bucket_total{bucket="3_10"} 3784
telemt_desync_frames_bucket_total{bucket="gt_10"} 4357
telemt_pool_swap_total 37
telemt_pool_force_close_total 1225
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 118
telemt_me_draining_writers_reap_progress_total 11694
telemt_me_writer_removed_unexpected_total 635
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1286
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11063
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1019
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10469
telemt_me_writer_teardown_success_total{mode="normal"} 12349
telemt_me_writer_teardown_noop_total 11696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24045
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.006096
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24045
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 118
telemt_me_refill_failed_total 2597
telemt_me_writer_restored_same_endpoint_total 793
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1784660
telemt_user_connections_current{user="hello"} 1296
telemt_user_octets_from_client{user="hello"} 52267263972 (48.68 GB)
telemt_user_octets_to_client{user="hello"} 765443721366 (712.88 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 686
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 15688.9 (4h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156462
telemt_connections_bad_total 1394
telemt_connections_current 303
telemt_connections_me_current 303
telemt_handshake_timeouts_total 3740
telemt_upstream_connect_attempt_total 7188
telemt_upstream_connect_success_total 7169
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 7187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4045
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 156
telemt_me_reconnect_success_total 95
telemt_me_reader_eof_total 95
telemt_me_idle_close_by_peer_total 95
telemt_me_route_drop_no_conn_total 44291
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 137207
telemt_me_endpoint_quarantine_total 139
telemt_me_single_endpoint_shadow_rotate_total 140
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 973
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 731
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 17
telemt_pool_force_close_total 400
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 6441
telemt_me_writer_removed_unexpected_total 93
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 424
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6112
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 398
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6041
telemt_me_writer_teardown_success_total{mode="normal"} 6536
telemt_me_writer_teardown_noop_total 6441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12977
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.776918
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12977
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 87
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 136973
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 2540021964 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 79934389252 (74.44 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 97886.9 (27h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6993850
telemt_connections_bad_total 709895
telemt_connections_current 1782
telemt_connections_me_current 1782
telemt_handshake_timeouts_total 199154
telemt_upstream_connect_attempt_total 37394
telemt_upstream_connect_success_total 37247
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 37357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18696
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_reconnect_attempts_total 1492
telemt_me_reconnect_success_total 780
telemt_me_reader_eof_total 757
telemt_me_idle_close_by_peer_total 757
telemt_me_route_drop_no_conn_total 2093712
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5295040
telemt_me_endpoint_quarantine_total 667
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 750
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 20449
telemt_desync_full_logged_total 6820
telemt_desync_suppressed_total 13629
telemt_desync_frames_bucket_total{bucket="1_2"} 4986
telemt_desync_frames_bucket_total{bucket="3_10"} 7413
telemt_desync_frames_bucket_total{bucket="gt_10"} 8050
telemt_pool_swap_total 108
telemt_pool_force_close_total 2945
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 367
telemt_me_draining_writers_reap_progress_total 33639
telemt_me_writer_removed_unexpected_total 733
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2720
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31666
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2857
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30694
telemt_me_writer_teardown_success_total{mode="normal"} 34386
telemt_me_writer_teardown_noop_total 33641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68027
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.556808
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68027
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 367
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 695
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 5270261
telemt_user_connections_current{user="hello"} 1782
telemt_user_octets_from_client{user="hello"} 106128413272 (98.84 GB)
telemt_user_octets_to_client{user="hello"} 2475977536516 (2.25 TB)
telemt_user_unique_ips_current{user="hello"} 786
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 97883.4 (27h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5998410
telemt_connections_bad_total 587992
telemt_connections_current 1723
telemt_connections_me_current 1723
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 166866
telemt_upstream_connect_attempt_total 53426
telemt_upstream_connect_success_total 53022
telemt_upstream_connect_fail_total 345
telemt_upstream_connect_attempts_per_request{bucket="1"} 53367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20499
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 345
telemt_me_reconnect_attempts_total 5296
telemt_me_reconnect_success_total 1087
telemt_me_reader_eof_total 964
telemt_me_idle_close_by_peer_total 964
telemt_me_seq_mismatch_total 41
telemt_me_route_drop_no_conn_total 2147383
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4665591
telemt_me_endpoint_quarantine_total 772
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 745
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 19230
telemt_desync_full_logged_total 6449
telemt_desync_suppressed_total 12781
telemt_desync_frames_bucket_total{bucket="1_2"} 4832
telemt_desync_frames_bucket_total{bucket="3_10"} 6997
telemt_desync_frames_bucket_total{bucket="gt_10"} 7401
telemt_pool_swap_total 106
telemt_pool_force_close_total 2908
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 365
telemt_me_draining_writers_reap_progress_total 32446
telemt_me_writer_removed_unexpected_total 976
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3199
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30267
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2685
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29538
telemt_me_writer_teardown_success_total{mode="normal"} 33466
telemt_me_writer_teardown_noop_total 32450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65916
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.859367
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65916
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 365
telemt_me_refill_failed_total 243
telemt_me_writer_restored_same_endpoint_total 843
telemt_me_writer_restored_fallback_total 54
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 4668897
telemt_user_connections_current{user="hello"} 1723
telemt_user_octets_from_client{user="hello"} 88543909177 (82.46 GB)
telemt_user_octets_to_client{user="hello"} 2005699469432 (1.82 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 764
telemt_user_unique_ips_recent_window{user="hello"} 158
```