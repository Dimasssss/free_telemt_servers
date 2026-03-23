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

# Server Metrics 2026-03-23 00:09:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 97412.0 (27h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3440566
telemt_connections_bad_total 291275
telemt_connections_current 698
telemt_connections_me_current 698
telemt_handshake_timeouts_total 107844
telemt_upstream_connect_attempt_total 36053
telemt_upstream_connect_success_total 36052
telemt_upstream_connect_attempts_per_request{bucket="1"} 36052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1373
telemt_me_reconnect_success_total 581
telemt_me_reader_eof_total 597
telemt_me_idle_close_by_peer_total 597
telemt_me_route_drop_no_conn_total 2975097
telemt_me_route_drop_channel_closed_total 1231
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2854672
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 675
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 757
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 12270
telemt_desync_full_logged_total 3844
telemt_desync_suppressed_total 8426
telemt_desync_frames_bucket_total{bucket="1_2"} 3322
telemt_desync_frames_bucket_total{bucket="3_10"} 4460
telemt_desync_frames_bucket_total{bucket="gt_10"} 4488
telemt_pool_swap_total 108
telemt_pool_force_close_total 3352
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 647
telemt_me_draining_writers_reap_progress_total 33025
telemt_me_writer_removed_unexpected_total 576
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2398
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30850
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3296
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29673
telemt_me_writer_teardown_success_total{mode="normal"} 33248
telemt_me_writer_teardown_noop_total 33036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66284
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 375.985886
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66284
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 647
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 519
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2843891
telemt_user_connections_current{user="hello"} 698
telemt_user_octets_from_client{user="hello"} 40750075040 (37.95 GB)
telemt_user_octets_to_client{user="hello"} 777752306392 (724.34 GB)
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 110778.3 (30h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3980583
telemt_connections_bad_total 363363
telemt_connections_current 463
telemt_connections_me_current 463
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100342
telemt_upstream_connect_attempt_total 68474
telemt_upstream_connect_success_total 67648
telemt_upstream_connect_fail_total 733
telemt_upstream_connect_attempts_per_request{bucket="1"} 68381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 733
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9803
telemt_me_reconnect_success_total 3547
telemt_me_reader_eof_total 3552
telemt_me_idle_close_by_peer_total 3552
telemt_me_route_drop_no_conn_total 3639137
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3165407
telemt_me_endpoint_quarantine_total 852
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 861
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 22
telemt_desync_total 12919
telemt_desync_full_logged_total 7240
telemt_desync_suppressed_total 5679
telemt_desync_frames_bucket_total{bucket="1_2"} 2934
telemt_desync_frames_bucket_total{bucket="3_10"} 5064
telemt_desync_frames_bucket_total{bucket="gt_10"} 4921
telemt_pool_swap_total 102
telemt_pool_force_close_total 3014
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 245
telemt_me_draining_writers_reap_progress_total 45054
telemt_me_writer_removed_unexpected_total 3485
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6031
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42538
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2556
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42040
telemt_me_writer_teardown_success_total{mode="normal"} 48569
telemt_me_writer_teardown_noop_total 45055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93624
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.561734
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93624
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 245
telemt_me_refill_failed_total 240
telemt_me_writer_restored_same_endpoint_total 3185
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 3177888
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 42910321470 (39.96 GB)
telemt_user_octets_to_client{user="hello"} 788433565388 (734.29 GB)
telemt_user_msgs_from_client{user="hello"} 47428
telemt_user_msgs_to_client{user="hello"} 180951
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 185638.2 (51h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16295457
telemt_connections_bad_total 1640375
telemt_connections_current 661
telemt_connections_me_current 661
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396830
telemt_upstream_connect_attempt_total 82880
telemt_upstream_connect_success_total 82777
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 82794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40357
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1710
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2972
telemt_me_reconnect_success_total 1550
telemt_me_reader_eof_total 1496
telemt_me_idle_close_by_peer_total 1494
telemt_me_route_drop_no_conn_total 14040621
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12944785
telemt_me_endpoint_quarantine_total 1223
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1394
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 53634
telemt_desync_full_logged_total 17014
telemt_desync_suppressed_total 36620
telemt_desync_frames_bucket_total{bucket="1_2"} 11943
telemt_desync_frames_bucket_total{bucket="3_10"} 20912
telemt_desync_frames_bucket_total{bucket="gt_10"} 20779
telemt_pool_swap_total 201
telemt_pool_force_close_total 6644
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1056
telemt_me_draining_writers_reap_progress_total 62465
telemt_me_writer_removed_unexpected_total 1442
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5375
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57805
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6174
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55821
telemt_me_writer_teardown_success_total{mode="normal"} 63180
telemt_me_writer_teardown_noop_total 62518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 125088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125698
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.547648
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125698
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1056
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1341
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 12944845
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 190878967369 (177.77 GB)
telemt_user_octets_to_client{user="hello"} 3482139672367 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 185639.6 (51h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11835318
telemt_connections_bad_total 1224552
telemt_connections_current 531
telemt_connections_me_current 531
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344389
telemt_upstream_connect_attempt_total 97275
telemt_upstream_connect_success_total 95956
telemt_upstream_connect_fail_total 866
telemt_upstream_connect_attempts_per_request{bucket="1"} 96822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40244
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3799
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 866
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4381
telemt_me_reconnect_success_total 1850
telemt_me_reader_eof_total 1715
telemt_me_idle_close_by_peer_total 1715
telemt_me_route_drop_no_conn_total 4551219
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8791266
telemt_me_endpoint_quarantine_total 1224
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1416
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 38675
telemt_desync_full_logged_total 13018
telemt_desync_suppressed_total 25657
telemt_desync_frames_bucket_total{bucket="1_2"} 9573
telemt_desync_frames_bucket_total{bucket="3_10"} 14857
telemt_desync_frames_bucket_total{bucket="gt_10"} 14245
telemt_pool_swap_total 198
telemt_pool_force_close_total 6001
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 708
telemt_me_draining_writers_reap_progress_total 60732
telemt_me_writer_removed_unexpected_total 1746
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5481
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56852
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5489
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54731
telemt_me_writer_teardown_success_total{mode="normal"} 62333
telemt_me_writer_teardown_noop_total 60757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123090
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.381653
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123090
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 708
telemt_me_refill_failed_total 136
telemt_me_writer_restored_same_endpoint_total 1580
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 8729038
telemt_user_connections_current{user="hello"} 531
telemt_user_octets_from_client{user="hello"} 217645001772 (202.70 GB)
telemt_user_octets_to_client{user="hello"} 3951166130163 (3.59 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 185603.8 (51h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11024316
telemt_connections_bad_total 968524
telemt_connections_current 439
telemt_connections_me_current 439
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345388
telemt_upstream_connect_attempt_total 81549
telemt_upstream_connect_success_total 79991
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 80196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38709
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2023
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5697
telemt_me_reconnect_success_total 2340
telemt_me_reader_eof_total 2082
telemt_me_idle_close_by_peer_total 2081
telemt_me_route_drop_no_conn_total 5333255
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8336988
telemt_me_endpoint_quarantine_total 1301
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1368
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_desync_total 37982
telemt_desync_full_logged_total 12595
telemt_desync_suppressed_total 25387
telemt_desync_frames_bucket_total{bucket="1_2"} 9596
telemt_desync_frames_bucket_total{bucket="3_10"} 14524
telemt_desync_frames_bucket_total{bucket="gt_10"} 13862
telemt_pool_swap_total 194
telemt_pool_force_close_total 5902
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 737
telemt_me_draining_writers_reap_progress_total 61087
telemt_me_writer_removed_unexpected_total 2234
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6232
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57019
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5331
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55185
telemt_me_writer_teardown_success_total{mode="normal"} 63251
telemt_me_writer_teardown_noop_total 61158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124409
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.677171
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124409
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 737
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 2031
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8328959
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 192532649491 (179.31 GB)
telemt_user_octets_to_client{user="hello"} 3461592109017 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 55883.7 (15h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11185012
telemt_connections_bad_total 668315
telemt_connections_current 926
telemt_connections_me_current 926
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 264833
telemt_upstream_connect_attempt_total 55492
telemt_upstream_connect_success_total 52645
telemt_upstream_connect_fail_total 1903
telemt_upstream_connect_attempts_per_request{bucket="1"} 54548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17931
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6005
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1903
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7464
telemt_me_reconnect_success_total 1159
telemt_me_reader_eof_total 735
telemt_me_idle_close_by_peer_total 734
telemt_me_route_drop_no_conn_total 25279078
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9289730
telemt_me_endpoint_quarantine_total 400
telemt_me_single_endpoint_outage_enter_total 85
telemt_me_single_endpoint_outage_exit_total 85
telemt_me_single_endpoint_outage_reconnect_attempt_total 158
telemt_me_single_endpoint_outage_reconnect_success_total 42
telemt_me_single_endpoint_quarantine_bypass_total 158
telemt_me_single_endpoint_shadow_rotate_total 438
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_me_writers_warm_current 35
telemt_desync_total 16256
telemt_desync_full_logged_total 4410
telemt_desync_suppressed_total 11846
telemt_desync_frames_bucket_total{bucket="1_2"} 3086
telemt_desync_frames_bucket_total{bucket="3_10"} 6605
telemt_desync_frames_bucket_total{bucket="gt_10"} 6565
telemt_pool_swap_total 57
telemt_pool_force_close_total 1914
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 472
telemt_me_draining_writers_reap_progress_total 17096
telemt_me_writer_removed_unexpected_total 1050
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2345
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15743
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1607
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15182
telemt_me_writer_teardown_success_total{mode="normal"} 18088
telemt_me_writer_teardown_noop_total 17115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35203
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.544262
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35203
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 472
telemt_me_refill_failed_total 336
telemt_me_writer_restored_same_endpoint_total 756
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 9315184
telemt_user_connections_current{user="hello"} 926
telemt_user_octets_from_client{user="hello"} 86581863890 (80.64 GB)
telemt_user_octets_to_client{user="hello"} 597258722805 (556.24 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 185610.3 (51h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10959658
telemt_connections_bad_total 942265
telemt_connections_current 511
telemt_connections_me_current 511
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241724
telemt_upstream_connect_attempt_total 110413
telemt_upstream_connect_success_total 109276
telemt_upstream_connect_fail_total 965
telemt_upstream_connect_attempts_per_request{bucket="1"} 110241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42269
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 965
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72823
telemt_me_reconnect_success_total 3031
telemt_me_reader_eof_total 2723
telemt_me_idle_close_by_peer_total 2721
telemt_me_route_drop_no_conn_total 5256309
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8649630
telemt_me_endpoint_quarantine_total 1239
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1397
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 46117
telemt_desync_full_logged_total 15786
telemt_desync_suppressed_total 30331
telemt_desync_frames_bucket_total{bucket="1_2"} 9371
telemt_desync_frames_bucket_total{bucket="3_10"} 17653
telemt_desync_frames_bucket_total{bucket="gt_10"} 19093
telemt_pool_swap_total 190
telemt_pool_force_close_total 5606
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 65231
telemt_me_writer_removed_unexpected_total 2754
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6735
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61283
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4857
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59625
telemt_me_writer_teardown_success_total{mode="normal"} 68018
telemt_me_writer_teardown_noop_total 65232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133250
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.219028
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133250
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2562
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8652666
telemt_user_connections_current{user="hello"} 511
telemt_user_octets_from_client{user="hello"} 194313050117 (180.97 GB)
telemt_user_octets_to_client{user="hello"} 3303311048564 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 233
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 122446.5 (34h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11654815
telemt_connections_bad_total 476380
telemt_connections_current 649
telemt_connections_me_current 649
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4759265
telemt_upstream_connect_attempt_total 58490
telemt_upstream_connect_success_total 58066
telemt_upstream_connect_fail_total 413
telemt_upstream_connect_attempts_per_request{bucket="1"} 58479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26624
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 214
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 413
telemt_me_reconnect_attempts_total 48825
telemt_me_reconnect_success_total 1772
telemt_me_reader_eof_total 1443
telemt_me_idle_close_by_peer_total 1442
telemt_me_route_drop_no_conn_total 4082775
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5599040
telemt_me_endpoint_quarantine_total 817
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 933
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_writers_active_current 42
telemt_me_writers_warm_current 13
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31480
telemt_desync_full_logged_total 10727
telemt_desync_suppressed_total 20753
telemt_desync_frames_bucket_total{bucket="1_2"} 6266
telemt_desync_frames_bucket_total{bucket="3_10"} 12414
telemt_desync_frames_bucket_total{bucket="gt_10"} 12800
telemt_pool_swap_total 129
telemt_pool_force_close_total 3823
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 44236
telemt_me_writer_removed_unexpected_total 1494
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3684
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42089
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3382
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40413
telemt_me_writer_teardown_success_total{mode="normal"} 45773
telemt_me_writer_teardown_noop_total 44243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90016
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.675841
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90016
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 2734
telemt_me_writer_restored_same_endpoint_total 1574
telemt_me_writer_restored_fallback_total 23
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5591615
telemt_user_connections_current{user="hello"} 649
telemt_user_octets_from_client{user="hello"} 118921359664 (110.75 GB)
telemt_user_octets_to_client{user="hello"} 2164120383118 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 103417.3 (28h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1501734
telemt_connections_bad_total 36667
telemt_connections_current 454
telemt_connections_me_current 454
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 30056
telemt_upstream_connect_attempt_total 48396
telemt_upstream_connect_success_total 48244
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 48368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25357
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 782
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2170
telemt_me_reconnect_success_total 887
telemt_me_reader_eof_total 868
telemt_me_idle_close_by_peer_total 868
telemt_me_route_drop_no_conn_total 514320
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1334052
telemt_me_endpoint_quarantine_total 836
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 852
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 8682
telemt_desync_full_logged_total 2572
telemt_desync_suppressed_total 6110
telemt_desync_frames_bucket_total{bucket="1_2"} 2340
telemt_desync_frames_bucket_total{bucket="3_10"} 3333
telemt_desync_frames_bucket_total{bucket="gt_10"} 3009
telemt_pool_swap_total 111
telemt_pool_force_close_total 2870
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 160
telemt_me_draining_writers_reap_progress_total 40787
telemt_me_writer_removed_unexpected_total 839
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3166
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38496
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2782
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37917
telemt_me_writer_teardown_success_total{mode="normal"} 41662
telemt_me_writer_teardown_noop_total 40791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82453
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.164069
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82453
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 160
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 752
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 1329892
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 25808819189 (24.04 GB)
telemt_user_octets_to_client{user="hello"} 571005574595 (531.79 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 185614.9 (51h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13294154
telemt_connections_bad_total 1595167
telemt_connections_current 598
telemt_connections_me_current 598
telemt_handshake_timeouts_total 387089
telemt_upstream_connect_attempt_total 72313
telemt_upstream_connect_success_total 71967
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 72177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36255
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2911
telemt_me_reconnect_success_total 1446
telemt_me_reader_eof_total 1431
telemt_me_idle_close_by_peer_total 1431
telemt_me_route_drop_no_conn_total 4479478
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10026624
telemt_me_endpoint_quarantine_total 1300
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1400
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 41937
telemt_desync_full_logged_total 13693
telemt_desync_suppressed_total 28244
telemt_desync_frames_bucket_total{bucket="1_2"} 10113
telemt_desync_frames_bucket_total{bucket="3_10"} 15417
telemt_desync_frames_bucket_total{bucket="gt_10"} 16407
telemt_pool_swap_total 206
telemt_pool_force_close_total 5536
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 674
telemt_me_draining_writers_reap_progress_total 65325
telemt_me_writer_removed_unexpected_total 1370
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5186
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61560
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5362
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59789
telemt_me_writer_teardown_success_total{mode="normal"} 66746
telemt_me_writer_teardown_noop_total 65327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 131564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 132073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 132073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 132073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 132073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 132073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 132073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 132073
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.743120
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 132073
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 674
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1268
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 9993353
telemt_user_connections_current{user="hello"} 598
telemt_user_octets_from_client{user="hello"} 194455177312 (181.10 GB)
telemt_user_octets_to_client{user="hello"} 4432459502648 (4.03 TB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 185611.5 (51h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11591518
telemt_connections_bad_total 1338673
telemt_connections_current 451
telemt_connections_me_current 451
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 309969
telemt_upstream_connect_attempt_total 99017
telemt_upstream_connect_success_total 98138
telemt_upstream_connect_fail_total 671
telemt_upstream_connect_attempts_per_request{bucket="1"} 98809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41855
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 671
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10329
telemt_me_reconnect_success_total 2542
telemt_me_reader_eof_total 2358
telemt_me_idle_close_by_peer_total 2357
telemt_me_seq_mismatch_total 95
telemt_me_route_drop_no_conn_total 5640123
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8933075
telemt_me_endpoint_quarantine_total 1483
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 1403
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 41669
telemt_desync_full_logged_total 13388
telemt_desync_suppressed_total 28281
telemt_desync_frames_bucket_total{bucket="1_2"} 10745
telemt_desync_frames_bucket_total{bucket="3_10"} 15312
telemt_desync_frames_bucket_total{bucket="gt_10"} 15612
telemt_pool_swap_total 196
telemt_pool_force_close_total 5329
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 661
telemt_me_draining_writers_reap_progress_total 65316
telemt_me_writer_removed_unexpected_total 2399
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6553
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61245
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4858
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59987
telemt_me_writer_teardown_success_total{mode="normal"} 67798
telemt_me_writer_teardown_noop_total 65321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 133119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 133119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 133119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 133119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 133119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 133119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 133119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 133119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 133119
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.441748
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 133119
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 661
telemt_me_refill_failed_total 403
telemt_me_writer_restored_same_endpoint_total 2051
telemt_me_writer_restored_fallback_total 130
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 8938411
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 157154068341 (146.36 GB)
telemt_user_octets_to_client{user="hello"} 3477853137511 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 202
```