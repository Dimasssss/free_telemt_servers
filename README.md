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

# Server Metrics 2026-03-21 20:54:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 87534.0 (24h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3107796
telemt_connections_bad_total 180418
telemt_connections_current 960
telemt_connections_me_current 960
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 97302
telemt_upstream_connect_attempt_total 35758
telemt_upstream_connect_success_total 35608
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 35715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21233
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 58
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1935
telemt_me_reconnect_success_total 772
telemt_me_reader_eof_total 741
telemt_me_idle_close_by_peer_total 741
telemt_me_route_drop_no_conn_total 2630246
telemt_me_route_drop_channel_closed_total 847
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2513697
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 592
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 684
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_writers_active_current 46
telemt_desync_total 10046
telemt_desync_full_logged_total 3512
telemt_desync_suppressed_total 6534
telemt_desync_frames_bucket_total{bucket="1_2"} 2181
telemt_desync_frames_bucket_total{bucket="3_10"} 3757
telemt_desync_frames_bucket_total{bucket="gt_10"} 4108
telemt_pool_swap_total 95
telemt_pool_force_close_total 2871
telemt_pool_stale_pick_total 31
telemt_me_writer_close_signal_drop_total 646
telemt_me_draining_writers_reap_progress_total 29367
telemt_me_writer_removed_unexpected_total 722
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2462
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27368
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2731
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 140
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26496
telemt_me_writer_teardown_success_total{mode="normal"} 29830
telemt_me_writer_teardown_noop_total 29375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59205
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 300.787607
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59205
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 646
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 663
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2513276
telemt_user_connections_current{user="hello"} 960
telemt_user_octets_from_client{user="hello"} 37199536757 (34.64 GB)
telemt_user_octets_to_client{user="hello"} 642608880850 (598.48 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 12671.6 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495567
telemt_connections_bad_total 22901
telemt_connections_current 1619
telemt_connections_me_current 1619
telemt_handshake_timeouts_total 17412
telemt_upstream_connect_attempt_total 4967
telemt_upstream_connect_success_total 4862
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 4954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2701
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_reconnect_attempts_total 333
telemt_me_reconnect_success_total 151
telemt_me_reader_eof_total 129
telemt_me_idle_close_by_peer_total 129
telemt_me_route_drop_no_conn_total 284149
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 401809
telemt_me_endpoint_quarantine_total 92
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 99
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 14
telemt_desync_total 1729
telemt_desync_full_logged_total 990
telemt_desync_suppressed_total 739
telemt_desync_frames_bucket_total{bucket="1_2"} 355
telemt_desync_frames_bucket_total{bucket="3_10"} 658
telemt_desync_frames_bucket_total{bucket="gt_10"} 716
telemt_pool_swap_total 13
telemt_pool_force_close_total 392
telemt_me_writer_close_signal_drop_total 35
telemt_me_draining_writers_reap_progress_total 4305
telemt_me_writer_removed_unexpected_total 122
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 362
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4059
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 385
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3913
telemt_me_writer_teardown_success_total{mode="normal"} 4421
telemt_me_writer_teardown_noop_total 4305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8726
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.244515
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8726
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 35
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 103
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 401317
telemt_user_connections_current{user="hello"} 1619
telemt_user_octets_from_client{user="hello"} 6569163220 (6.12 GB)
telemt_user_octets_to_client{user="hello"} 123752789672 (115.25 GB)
telemt_user_unique_ips_current{user="hello"} 953
telemt_user_unique_ips_recent_window{user="hello"} 283
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 87531.5 (24h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6959942
telemt_connections_bad_total 539153
telemt_connections_current 2715
telemt_connections_me_current 2715
telemt_handshake_timeouts_total 217378
telemt_upstream_connect_attempt_total 31428
telemt_upstream_connect_success_total 31365
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 31372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17103
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 128
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1352
telemt_me_reconnect_success_total 675
telemt_me_reader_eof_total 684
telemt_me_idle_close_by_peer_total 684
telemt_me_route_drop_no_conn_total 4381196
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5694844
telemt_me_endpoint_quarantine_total 544
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 647
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 23600
telemt_desync_full_logged_total 7849
telemt_desync_suppressed_total 15751
telemt_desync_frames_bucket_total{bucket="1_2"} 4932
telemt_desync_frames_bucket_total{bucket="3_10"} 9354
telemt_desync_frames_bucket_total{bucket="gt_10"} 9314
telemt_pool_swap_total 94
telemt_pool_force_close_total 3182
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 517
telemt_me_draining_writers_reap_progress_total 28618
telemt_me_writer_removed_unexpected_total 658
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2456
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26423
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2949
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 233
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25436
telemt_me_writer_teardown_success_total{mode="normal"} 28879
telemt_me_writer_teardown_noop_total 28655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57534
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 141.839820
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57534
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 517
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 604
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 5687967
telemt_user_connections_current{user="hello"} 2715
telemt_user_octets_from_client{user="hello"} 98119362292 (91.38 GB)
telemt_user_octets_to_client{user="hello"} 1797693711268 (1.63 TB)
telemt_user_unique_ips_current{user="hello"} 1052
telemt_user_unique_ips_recent_window{user="hello"} 417
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 87532.7 (24h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5643403
telemt_connections_bad_total 544859
telemt_connections_current 3246
telemt_connections_me_current 3246
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 185013
telemt_upstream_connect_attempt_total 35527
telemt_upstream_connect_success_total 35209
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 35373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 542
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1674
telemt_me_reconnect_success_total 700
telemt_me_reader_eof_total 674
telemt_me_idle_close_by_peer_total 674
telemt_me_route_drop_no_conn_total 1950509
telemt_me_route_drop_channel_closed_total 224
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4221567
telemt_me_endpoint_quarantine_total 539
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 668
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_writers_active_current 43
telemt_desync_total 20136
telemt_desync_full_logged_total 6684
telemt_desync_suppressed_total 13452
telemt_desync_frames_bucket_total{bucket="1_2"} 4924
telemt_desync_frames_bucket_total{bucket="3_10"} 7790
telemt_desync_frames_bucket_total{bucket="gt_10"} 7422
telemt_pool_swap_total 96
telemt_pool_force_close_total 2916
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 331
telemt_me_draining_writers_reap_progress_total 27378
telemt_me_writer_removed_unexpected_total 653
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2374
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25586
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2719
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 197
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24462
telemt_me_writer_teardown_success_total{mode="normal"} 27960
telemt_me_writer_teardown_noop_total 27383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55343
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.630906
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55343
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 331
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 600
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 4213828
telemt_user_connections_current{user="hello"} 3246
telemt_user_octets_from_client{user="hello"} 127049771777 (118.32 GB)
telemt_user_octets_to_client{user="hello"} 1935653274599 (1.76 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1195
telemt_user_unique_ips_recent_window{user="hello"} 711
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 87496.8 (24h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5566414
telemt_connections_bad_total 500090
telemt_connections_current 2644
telemt_connections_me_current 2644
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 169675
telemt_upstream_connect_attempt_total 41955
telemt_upstream_connect_success_total 41685
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 41820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18281
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1040
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1731
telemt_me_reconnect_success_total 764
telemt_me_reader_eof_total 708
telemt_me_idle_close_by_peer_total 708
telemt_me_route_drop_no_conn_total 2002209
telemt_me_route_drop_channel_closed_total 99
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4204781
telemt_me_endpoint_quarantine_total 592
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 652
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
telemt_me_writers_active_current 43
telemt_desync_total 19883
telemt_desync_full_logged_total 6514
telemt_desync_suppressed_total 13369
telemt_desync_frames_bucket_total{bucket="1_2"} 4949
telemt_desync_frames_bucket_total{bucket="3_10"} 7535
telemt_desync_frames_bucket_total{bucket="gt_10"} 7399
telemt_pool_swap_total 94
telemt_pool_force_close_total 2795
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 335
telemt_me_draining_writers_reap_progress_total 28835
telemt_me_writer_removed_unexpected_total 678
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2466
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27050
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2582
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26040
telemt_me_writer_teardown_success_total{mode="normal"} 29516
telemt_me_writer_teardown_noop_total 28845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58361
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.374266
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58361
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 335
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 660
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 4206813
telemt_user_connections_current{user="hello"} 2644
telemt_user_octets_from_client{user="hello"} 122588678339 (114.17 GB)
telemt_user_octets_to_client{user="hello"} 1921469653091 (1.75 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1012
telemt_user_unique_ips_recent_window{user="hello"} 745
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 87536.8 (24h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19198141
telemt_connections_bad_total 1256619
telemt_connections_current 3638
telemt_connections_me_current 3638
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 536022
telemt_upstream_connect_attempt_total 181390
telemt_upstream_connect_success_total 164152
telemt_upstream_connect_fail_total 15805
telemt_upstream_connect_attempts_per_request{bucket="1"} 179957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36967
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8848
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15805
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59635
telemt_me_reconnect_success_total 1892
telemt_me_reader_eof_total 1249
telemt_me_idle_close_by_peer_total 1248
telemt_me_route_drop_no_conn_total 39116257
telemt_me_route_drop_channel_closed_total 116
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15777955
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 645
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 239
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 239
telemt_me_single_endpoint_shadow_rotate_total 682
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_me_writers_active_current 85
telemt_desync_total 29593
telemt_desync_full_logged_total 8726
telemt_desync_suppressed_total 20867
telemt_desync_frames_bucket_total{bucket="1_2"} 6490
telemt_desync_frames_bucket_total{bucket="3_10"} 13101
telemt_desync_frames_bucket_total{bucket="gt_10"} 10002
telemt_pool_swap_total 89
telemt_pool_force_close_total 2975
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 26877
telemt_me_writer_removed_unexpected_total 1782
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3697
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24706
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2513
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 462
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23902
telemt_me_writer_teardown_success_total{mode="normal"} 28403
telemt_me_writer_teardown_noop_total 26903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55306
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 203.333270
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55306
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 3519
telemt_me_writer_restored_same_endpoint_total 1316
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14223
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 15903176
telemt_user_connections_current{user="hello"} 3638
telemt_user_octets_from_client{user="hello"} 153526851558 (142.98 GB)
telemt_user_octets_to_client{user="hello"} 978812764318 (911.59 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1446
telemt_user_unique_ips_recent_window{user="hello"} 487
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 87503.7 (24h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5462365
telemt_connections_bad_total 524460
telemt_connections_current 2467
telemt_connections_me_current 2467
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 112438
telemt_upstream_connect_attempt_total 45079
telemt_upstream_connect_success_total 44584
telemt_upstream_connect_fail_total 411
telemt_upstream_connect_attempts_per_request{bucket="1"} 44995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18550
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 411
telemt_me_reconnect_attempts_total 11082
telemt_me_reconnect_success_total 1278
telemt_me_reader_eof_total 1205
telemt_me_idle_close_by_peer_total 1205
telemt_me_route_drop_no_conn_total 2277131
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4243462
telemt_me_endpoint_quarantine_total 538
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 652
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 21086
telemt_desync_full_logged_total 7307
telemt_desync_suppressed_total 13779
telemt_desync_frames_bucket_total{bucket="1_2"} 4025
telemt_desync_frames_bucket_total{bucket="3_10"} 8212
telemt_desync_frames_bucket_total{bucket="gt_10"} 8849
telemt_pool_swap_total 89
telemt_pool_force_close_total 2608
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 328
telemt_me_draining_writers_reap_progress_total 29603
telemt_me_writer_removed_unexpected_total 1185
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3021
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27780
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2243
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 365
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26995
telemt_me_writer_teardown_success_total{mode="normal"} 30801
telemt_me_writer_teardown_noop_total 29604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60405
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.444006
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60405
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 328
telemt_me_refill_failed_total 591
telemt_me_writer_restored_same_endpoint_total 1079
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 1512
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 4233057
telemt_user_connections_current{user="hello"} 2467
telemt_user_octets_from_client{user="hello"} 113545740333 (105.75 GB)
telemt_user_octets_to_client{user="hello"} 1716519682187 (1.56 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 924
telemt_user_unique_ips_recent_window{user="hello"} 411
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 24339.5 (6h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3201826
telemt_connections_bad_total 117595
telemt_connections_current 3195
telemt_connections_me_current 3195
telemt_handshake_timeouts_total 1373839
telemt_upstream_connect_attempt_total 7876
telemt_upstream_connect_success_total 7770
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 7870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_reconnect_attempts_total 2206
telemt_me_reconnect_success_total 265
telemt_me_reader_eof_total 207
telemt_me_idle_close_by_peer_total 207
telemt_me_route_drop_no_conn_total 922955
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1516354
telemt_me_endpoint_quarantine_total 121
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 178
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
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 10
telemt_desync_total 8392
telemt_desync_full_logged_total 2786
telemt_desync_suppressed_total 5606
telemt_desync_frames_bucket_total{bucket="1_2"} 1495
telemt_desync_frames_bucket_total{bucket="3_10"} 3175
telemt_desync_frames_bucket_total{bucket="gt_10"} 3722
telemt_pool_swap_total 25
telemt_pool_force_close_total 815
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 6848
telemt_me_writer_removed_unexpected_total 224
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 646
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6434
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 107
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6033
telemt_me_writer_teardown_success_total{mode="normal"} 7080
telemt_me_writer_teardown_noop_total 6849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13929
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.139718
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13929
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 216
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 192
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1511982
telemt_user_connections_current{user="hello"} 3195
telemt_user_octets_from_client{user="hello"} 45004910780 (41.91 GB)
telemt_user_octets_to_client{user="hello"} 631321021852 (587.96 GB)
telemt_user_unique_ips_current{user="hello"} 1517
telemt_user_unique_ips_recent_window{user="hello"} 344
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 5310.3 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58456
telemt_connections_bad_total 175
telemt_connections_current 599
telemt_connections_me_current 599
telemt_handshake_timeouts_total 836
telemt_upstream_connect_attempt_total 2289
telemt_upstream_connect_success_total 2282
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 57
telemt_me_reconnect_success_total 26
telemt_me_reader_eof_total 26
telemt_me_idle_close_by_peer_total 26
telemt_me_route_drop_no_conn_total 17336
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51651
telemt_me_endpoint_quarantine_total 35
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 383
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 265
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 121
telemt_pool_swap_total 5
telemt_pool_force_close_total 134
telemt_me_writer_close_signal_drop_total 4
telemt_me_draining_writers_reap_progress_total 1966
telemt_me_writer_removed_unexpected_total 26
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 127
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1865
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 134
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1832
telemt_me_writer_teardown_success_total{mode="normal"} 1992
telemt_me_writer_teardown_noop_total 1966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3958
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.265100
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3958
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 4
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 23
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 51570
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 1108395320 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 40197198016 (37.44 GB)
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 87508.0 (24h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6487699
telemt_connections_bad_total 662357
telemt_connections_current 3006
telemt_connections_me_current 3006
telemt_handshake_timeouts_total 187383
telemt_upstream_connect_attempt_total 33160
telemt_upstream_connect_success_total 33027
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 33123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_reconnect_attempts_total 1399
telemt_me_reconnect_success_total 705
telemt_me_reader_eof_total 679
telemt_me_idle_close_by_peer_total 679
telemt_me_route_drop_no_conn_total 2005141
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4974728
telemt_me_endpoint_quarantine_total 585
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 666
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_me_writers_active_current 46
telemt_desync_total 18937
telemt_desync_full_logged_total 6315
telemt_desync_suppressed_total 12622
telemt_desync_frames_bucket_total{bucket="1_2"} 4612
telemt_desync_frames_bucket_total{bucket="3_10"} 6900
telemt_desync_frames_bucket_total{bucket="gt_10"} 7425
telemt_pool_swap_total 97
telemt_pool_force_close_total 2652
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 336
telemt_me_draining_writers_reap_progress_total 29772
telemt_me_writer_removed_unexpected_total 662
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2423
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28018
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2568
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 84
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27120
telemt_me_writer_teardown_success_total{mode="normal"} 30441
telemt_me_writer_teardown_noop_total 29774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60215
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.865903
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60215
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 336
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 629
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4950530
telemt_user_connections_current{user="hello"} 3006
telemt_user_octets_from_client{user="hello"} 98790520848 (92.01 GB)
telemt_user_octets_to_client{user="hello"} 2312086901352 (2.10 TB)
telemt_user_unique_ips_current{user="hello"} 1106
telemt_user_unique_ips_recent_window{user="hello"} 817
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 87504.8 (24h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5508291
telemt_connections_bad_total 515404
telemt_connections_current 2740
telemt_connections_me_current 2740
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 157756
telemt_upstream_connect_attempt_total 49564
telemt_upstream_connect_success_total 49195
telemt_upstream_connect_fail_total 310
telemt_upstream_connect_attempts_per_request{bucket="1"} 49505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 310
telemt_me_reconnect_attempts_total 4519
telemt_me_reconnect_success_total 998
telemt_me_reader_eof_total 885
telemt_me_idle_close_by_peer_total 885
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2059834
telemt_me_route_drop_channel_closed_total 186
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4338783
telemt_me_endpoint_quarantine_total 693
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 666
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
telemt_me_writers_active_current 42
telemt_desync_total 17669
telemt_desync_full_logged_total 5952
telemt_desync_suppressed_total 11717
telemt_desync_frames_bucket_total{bucket="1_2"} 4370
telemt_desync_frames_bucket_total{bucket="3_10"} 6491
telemt_desync_frames_bucket_total{bucket="gt_10"} 6808
telemt_pool_swap_total 95
telemt_pool_force_close_total 2582
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 333
telemt_me_draining_writers_reap_progress_total 28999
telemt_me_writer_removed_unexpected_total 897
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2913
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27024
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2384
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 198
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26417
telemt_me_writer_teardown_success_total{mode="normal"} 29937
telemt_me_writer_teardown_noop_total 29003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58940
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.026512
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58940
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 333
telemt_me_refill_failed_total 201
telemt_me_writer_restored_same_endpoint_total 769
telemt_me_writer_restored_fallback_total 48
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 4342863
telemt_user_connections_current{user="hello"} 2740
telemt_user_octets_from_client{user="hello"} 83277471033 (77.56 GB)
telemt_user_octets_to_client{user="hello"} 1826276136020 (1.66 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 999
telemt_user_unique_ips_recent_window{user="hello"} 704
```