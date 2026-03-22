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

# Server Metrics 2026-03-22 14:47:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 63674.8 (17h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2099869
telemt_connections_bad_total 100456
telemt_connections_current 2255
telemt_connections_me_current 2255
telemt_handshake_timeouts_total 83421
telemt_upstream_connect_attempt_total 23699
telemt_upstream_connect_success_total 23698
telemt_upstream_connect_attempts_per_request{bucket="1"} 23698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 975
telemt_me_reconnect_success_total 399
telemt_me_reader_eof_total 402
telemt_me_idle_close_by_peer_total 402
telemt_me_route_drop_no_conn_total 1533302
telemt_me_route_drop_channel_closed_total 682
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1784143
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 501
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
telemt_me_writers_active_current 44
telemt_desync_total 9335
telemt_desync_full_logged_total 2883
telemt_desync_suppressed_total 6452
telemt_desync_frames_bucket_total{bucket="1_2"} 2570
telemt_desync_frames_bucket_total{bucket="3_10"} 3496
telemt_desync_frames_bucket_total{bucket="gt_10"} 3269
telemt_pool_swap_total 70
telemt_pool_force_close_total 2139
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 366
telemt_me_draining_writers_reap_progress_total 21625
telemt_me_writer_removed_unexpected_total 389
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1559
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20276
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2095
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 44
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19486
telemt_me_writer_teardown_success_total{mode="normal"} 21835
telemt_me_writer_teardown_noop_total 21629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43464
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 176.820523
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43464
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 366
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 350
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1781105
telemt_user_connections_current{user="hello"} 2255
telemt_user_octets_from_client{user="hello"} 27847513720 (25.94 GB)
telemt_user_octets_to_client{user="hello"} 505598744780 (470.88 GB)
telemt_user_unique_ips_current{user="hello"} 750
telemt_user_unique_ips_recent_window{user="hello"} 613
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 77041.0 (21h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3389842
telemt_connections_bad_total 307002
telemt_connections_current 1493
telemt_connections_me_current 1493
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 79677
telemt_upstream_connect_attempt_total 49084
telemt_upstream_connect_success_total 48491
telemt_upstream_connect_fail_total 524
telemt_upstream_connect_attempts_per_request{bucket="1"} 49015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19611
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 524
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5591
telemt_me_reconnect_success_total 1899
telemt_me_reader_eof_total 1822
telemt_me_idle_close_by_peer_total 1822
telemt_me_route_drop_no_conn_total 3326450
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2685163
telemt_me_endpoint_quarantine_total 630
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 600
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
telemt_me_writers_active_current 44
telemt_desync_total 10363
telemt_desync_full_logged_total 5759
telemt_desync_suppressed_total 4604
telemt_desync_frames_bucket_total{bucket="1_2"} 2446
telemt_desync_frames_bucket_total{bucket="3_10"} 4092
telemt_desync_frames_bucket_total{bucket="gt_10"} 3825
telemt_pool_swap_total 74
telemt_pool_force_close_total 2174
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 185
telemt_me_draining_writers_reap_progress_total 30523
telemt_me_writer_removed_unexpected_total 1780
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3535
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28769
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 292
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28349
telemt_me_writer_teardown_success_total{mode="normal"} 32304
telemt_me_writer_teardown_noop_total 30523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62827
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.335107
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62827
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 185
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1610
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 2696572
telemt_user_connections_current{user="hello"} 1493
telemt_user_octets_from_client{user="hello"} 32219618907 (30.01 GB)
telemt_user_octets_to_client{user="hello"} 593338727010 (552.59 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1004
telemt_user_unique_ips_recent_window{user="hello"} 739
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 151900.9 (42h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14762785
telemt_connections_bad_total 1313885
telemt_connections_current 5206
telemt_connections_me_current 5206
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 362548
telemt_upstream_connect_attempt_total 69220
telemt_upstream_connect_success_total 69126
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 69143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32493
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1656
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2535
telemt_me_reconnect_success_total 1319
telemt_me_reader_eof_total 1257
telemt_me_idle_close_by_peer_total 1256
telemt_me_route_drop_no_conn_total 13308160
telemt_me_route_drop_channel_closed_total 132
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11838718
telemt_me_endpoint_quarantine_total 965
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1129
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 47739
telemt_desync_full_logged_total 15034
telemt_desync_suppressed_total 32705
telemt_desync_frames_bucket_total{bucket="1_2"} 10793
telemt_desync_frames_bucket_total{bucket="3_10"} 18689
telemt_desync_frames_bucket_total{bucket="gt_10"} 18257
telemt_pool_swap_total 163
telemt_pool_force_close_total 5547
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 904
telemt_me_draining_writers_reap_progress_total 50009
telemt_me_writer_removed_unexpected_total 1212
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4358
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46183
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5099
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 448
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44462
telemt_me_writer_teardown_success_total{mode="normal"} 50541
telemt_me_writer_teardown_noop_total 50058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100599
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 286.437120
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100599
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 904
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 1132
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 11840412
telemt_user_connections_current{user="hello"} 5206
telemt_user_octets_from_client{user="hello"} 166031850613 (154.63 GB)
telemt_user_octets_to_client{user="hello"} 3061946652979 (2.78 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 2033
telemt_user_unique_ips_recent_window{user="hello"} 1113
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 151902.2 (42h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10731240
telemt_connections_bad_total 1033521
telemt_connections_current 4719
telemt_connections_me_current 4719
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 317724
telemt_upstream_connect_attempt_total 81237
telemt_upstream_connect_success_total 80091
telemt_upstream_connect_fail_total 823
telemt_upstream_connect_attempts_per_request{bucket="1"} 80914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32289
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3683
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 823
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3782
telemt_me_reconnect_success_total 1494
telemt_me_reader_eof_total 1367
telemt_me_idle_close_by_peer_total 1367
telemt_me_route_drop_no_conn_total 4253358
telemt_me_route_drop_channel_closed_total 465
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8010831
telemt_me_endpoint_quarantine_total 954
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1151
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 35694
telemt_desync_full_logged_total 11992
telemt_desync_suppressed_total 23702
telemt_desync_frames_bucket_total{bucket="1_2"} 8785
telemt_desync_frames_bucket_total{bucket="3_10"} 13742
telemt_desync_frames_bucket_total{bucket="gt_10"} 13167
telemt_pool_swap_total 162
telemt_pool_force_close_total 5012
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 633
telemt_me_draining_writers_reap_progress_total 48217
telemt_me_writer_removed_unexpected_total 1399
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4399
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45074
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4575
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 437
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43205
telemt_me_writer_teardown_success_total{mode="normal"} 49473
telemt_me_writer_teardown_noop_total 48232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97705
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 96.549118
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97705
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 633
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 1265
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 7949872
telemt_user_connections_current{user="hello"} 4719
telemt_user_octets_from_client{user="hello"} 200619799905 (186.84 GB)
telemt_user_octets_to_client{user="hello"} 3581107719106 (3.26 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1958
telemt_user_unique_ips_recent_window{user="hello"} 653
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 151866.4 (42h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10180999
telemt_connections_bad_total 866073
telemt_connections_current 4249
telemt_connections_me_current 4249
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 326515
telemt_upstream_connect_attempt_total 66684
telemt_upstream_connect_success_total 65763
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 65945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30976
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4537
telemt_me_reconnect_success_total 1844
telemt_me_reader_eof_total 1597
telemt_me_idle_close_by_peer_total 1596
telemt_me_route_drop_no_conn_total 5036990
telemt_me_route_drop_channel_closed_total 345
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7690161
telemt_me_endpoint_quarantine_total 1047
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1113
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_me_writers_active_current 44
telemt_desync_total 35420
telemt_desync_full_logged_total 11722
telemt_desync_suppressed_total 23698
telemt_desync_frames_bucket_total{bucket="1_2"} 8966
telemt_desync_frames_bucket_total{bucket="3_10"} 13557
telemt_desync_frames_bucket_total{bucket="gt_10"} 12897
telemt_pool_swap_total 158
telemt_pool_force_close_total 4960
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 669
telemt_me_draining_writers_reap_progress_total 48846
telemt_me_writer_removed_unexpected_total 1741
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4886
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45609
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4428
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 532
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43886
telemt_me_writer_teardown_success_total{mode="normal"} 50495
telemt_me_writer_teardown_noop_total 48916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99411
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3167.385343
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99411
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 669
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 1601
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 7683534
telemt_user_connections_current{user="hello"} 4249
telemt_user_octets_from_client{user="hello"} 178607611057 (166.34 GB)
telemt_user_octets_to_client{user="hello"} 3188754896021 (2.90 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1755
telemt_user_unique_ips_recent_window{user="hello"} 623
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 22146.0 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9377212
telemt_connections_bad_total 587012
telemt_connections_current 7058
telemt_connections_me_current 7058
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 150044
telemt_upstream_connect_attempt_total 29420
telemt_upstream_connect_success_total 27961
telemt_upstream_connect_fail_total 1034
telemt_upstream_connect_attempts_per_request{bucket="1"} 28995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15522
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7135
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4761
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1034
telemt_me_keepalive_timeout_total 862
telemt_me_reconnect_attempts_total 5524
telemt_me_reconnect_success_total 603
telemt_me_reader_eof_total 396
telemt_me_idle_close_by_peer_total 396
telemt_me_route_drop_no_conn_total 23173505
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7808642
telemt_me_endpoint_quarantine_total 137
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 63
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 63
telemt_me_single_endpoint_shadow_rotate_total 169
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 11700
telemt_desync_full_logged_total 3001
telemt_desync_suppressed_total 8699
telemt_desync_frames_bucket_total{bucket="1_2"} 2060
telemt_desync_frames_bucket_total{bucket="3_10"} 4735
telemt_desync_frames_bucket_total{bucket="gt_10"} 4905
telemt_pool_swap_total 20
telemt_pool_force_close_total 855
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 307
telemt_me_draining_writers_reap_progress_total 5881
telemt_me_writer_removed_unexpected_total 515
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1012
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5347
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 590
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 265
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5026
telemt_me_writer_teardown_success_total{mode="normal"} 6359
telemt_me_writer_teardown_noop_total 5885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12244
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 28.512679
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12244
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 307
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 431
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 7823285
telemt_user_connections_current{user="hello"} 7058
telemt_user_octets_from_client{user="hello"} 44740101067 (41.67 GB)
telemt_user_octets_to_client{user="hello"} 228399680100 (212.71 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2599
telemt_user_unique_ips_recent_window{user="hello"} 1443
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 151872.9 (42h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9904267
telemt_connections_bad_total 821588
telemt_connections_current 5262
telemt_connections_me_current 5262
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 216487
telemt_upstream_connect_attempt_total 91156
telemt_upstream_connect_success_total 90236
telemt_upstream_connect_fail_total 797
telemt_upstream_connect_attempts_per_request{bucket="1"} 91033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33038
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1256
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 797
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71500
telemt_me_reconnect_success_total 2481
telemt_me_reader_eof_total 2213
telemt_me_idle_close_by_peer_total 2212
telemt_me_route_drop_no_conn_total 4903543
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7820435
telemt_me_endpoint_quarantine_total 1017
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1130
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 40229
telemt_desync_full_logged_total 13764
telemt_desync_suppressed_total 26465
telemt_desync_frames_bucket_total{bucket="1_2"} 8178
telemt_desync_frames_bucket_total{bucket="3_10"} 15598
telemt_desync_frames_bucket_total{bucket="gt_10"} 16453
telemt_pool_swap_total 155
telemt_pool_force_close_total 4625
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 565
telemt_me_draining_writers_reap_progress_total 51626
telemt_me_writer_removed_unexpected_total 2239
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5462
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48421
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3973
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 652
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47001
telemt_me_writer_teardown_success_total{mode="normal"} 53883
telemt_me_writer_teardown_noop_total 51627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105510
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.048384
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105510
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 565
telemt_me_refill_failed_total 4258
telemt_me_writer_restored_same_endpoint_total 2084
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 7821018
telemt_user_connections_current{user="hello"} 5262
telemt_user_octets_from_client{user="hello"} 178677331987 (166.41 GB)
telemt_user_octets_to_client{user="hello"} 2947235160433 (2.68 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2087
telemt_user_unique_ips_recent_window{user="hello"} 695
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 88708.8 (24h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10150773
telemt_connections_bad_total 371090
telemt_connections_current 4860
telemt_connections_me_current 4860
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4274105
telemt_upstream_connect_attempt_total 43262
telemt_upstream_connect_success_total 42948
telemt_upstream_connect_fail_total 305
telemt_upstream_connect_attempts_per_request{bucket="1"} 43253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 305
telemt_me_reconnect_attempts_total 47952
telemt_me_reconnect_success_total 1466
telemt_me_reader_eof_total 1132
telemt_me_idle_close_by_peer_total 1132
telemt_me_route_drop_no_conn_total 3782275
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4883942
telemt_me_endpoint_quarantine_total 581
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 667
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 26663
telemt_desync_full_logged_total 8992
telemt_desync_suppressed_total 17671
telemt_desync_frames_bucket_total{bucket="1_2"} 5395
telemt_desync_frames_bucket_total{bucket="3_10"} 10540
telemt_desync_frames_bucket_total{bucket="gt_10"} 10728
telemt_pool_swap_total 93
telemt_pool_force_close_total 2889
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 298
telemt_me_draining_writers_reap_progress_total 30520
telemt_me_writer_removed_unexpected_total 1197
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2761
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28984
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2476
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 413
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27631
telemt_me_writer_teardown_success_total{mode="normal"} 31745
telemt_me_writer_teardown_noop_total 30527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62272
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.296745
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62272
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 298
telemt_me_refill_failed_total 2702
telemt_me_writer_restored_same_endpoint_total 1308
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4877966
telemt_user_connections_current{user="hello"} 4860
telemt_user_octets_from_client{user="hello"} 105503281372 (98.26 GB)
telemt_user_octets_to_client{user="hello"} 1837831585886 (1.67 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1835
telemt_user_unique_ips_recent_window{user="hello"} 713
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 69679.7 (19h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 866130
telemt_connections_bad_total 10992
telemt_connections_current 1117
telemt_connections_me_current 1117
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 16863
telemt_upstream_connect_attempt_total 34904
telemt_upstream_connect_success_total 34818
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 34888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18455
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 465
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_reconnect_attempts_total 1584
telemt_me_reconnect_success_total 669
telemt_me_reader_eof_total 644
telemt_me_idle_close_by_peer_total 644
telemt_me_route_drop_no_conn_total 297269
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 770553
telemt_me_endpoint_quarantine_total 619
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 581
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 4269
telemt_desync_full_logged_total 1297
telemt_desync_suppressed_total 2972
telemt_desync_frames_bucket_total{bucket="1_2"} 1014
telemt_desync_frames_bucket_total{bucket="3_10"} 1695
telemt_desync_frames_bucket_total{bucket="gt_10"} 1560
telemt_pool_swap_total 74
telemt_pool_force_close_total 1853
telemt_me_writer_close_signal_drop_total 107
telemt_me_draining_writers_reap_progress_total 28766
telemt_me_writer_removed_unexpected_total 623
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2209
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27203
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1775
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26913
telemt_me_writer_teardown_success_total{mode="normal"} 29412
telemt_me_writer_teardown_noop_total 28768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58180
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.317712
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58180
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 107
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 571
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 771709
telemt_user_connections_current{user="hello"} 1117
telemt_user_octets_from_client{user="hello"} 14457446853 (13.46 GB)
telemt_user_octets_to_client{user="hello"} 358313889411 (333.71 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 392
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 151877.9 (42h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12112137
telemt_connections_bad_total 1410636
telemt_connections_current 6362
telemt_connections_me_current 6362
telemt_handshake_timeouts_total 331930
telemt_upstream_connect_attempt_total 56941
telemt_upstream_connect_success_total 56718
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 56891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28706
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_reconnect_attempts_total 2213
telemt_me_reconnect_success_total 1189
telemt_me_reader_eof_total 1151
telemt_me_idle_close_by_peer_total 1151
telemt_me_route_drop_no_conn_total 3948263
telemt_me_route_drop_channel_closed_total 118
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9133700
telemt_me_endpoint_quarantine_total 1029
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1135
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_me_writers_active_current 44
telemt_desync_total 37465
telemt_desync_full_logged_total 12273
telemt_desync_suppressed_total 25192
telemt_desync_frames_bucket_total{bucket="1_2"} 8923
telemt_desync_frames_bucket_total{bucket="3_10"} 13875
telemt_desync_frames_bucket_total{bucket="gt_10"} 14667
telemt_pool_swap_total 168
telemt_pool_force_close_total 4647
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 596
telemt_me_draining_writers_reap_progress_total 51278
telemt_me_writer_removed_unexpected_total 1107
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4216
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48199
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4476
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 171
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46631
telemt_me_writer_teardown_success_total{mode="normal"} 52415
telemt_me_writer_teardown_noop_total 51280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103695
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.522341
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103695
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 596
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1043
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 9103407
telemt_user_connections_current{user="hello"} 6362
telemt_user_octets_from_client{user="hello"} 175586279080 (163.53 GB)
telemt_user_octets_to_client{user="hello"} 4053120292200 (3.69 TB)
telemt_user_unique_ips_current{user="hello"} 2327
telemt_user_unique_ips_recent_window{user="hello"} 840
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 151874.2 (42h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10475777
telemt_connections_bad_total 1167945
telemt_connections_current 5015
telemt_connections_me_current 5015
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 271509
telemt_upstream_connect_attempt_total 82497
telemt_upstream_connect_success_total 81883
telemt_upstream_connect_fail_total 532
telemt_upstream_connect_attempts_per_request{bucket="1"} 82415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33754
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2012
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 532
telemt_me_reconnect_attempts_total 8756
telemt_me_reconnect_success_total 1975
telemt_me_reader_eof_total 1840
telemt_me_idle_close_by_peer_total 1840
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 5001238
telemt_me_route_drop_channel_closed_total 334
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8087247
telemt_me_endpoint_quarantine_total 1155
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1140
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 37081
telemt_desync_full_logged_total 12008
telemt_desync_suppressed_total 25073
telemt_desync_frames_bucket_total{bucket="1_2"} 9230
telemt_desync_frames_bucket_total{bucket="3_10"} 13805
telemt_desync_frames_bucket_total{bucket="gt_10"} 14046
telemt_pool_swap_total 161
telemt_pool_force_close_total 4504
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 585
telemt_me_draining_writers_reap_progress_total 50569
telemt_me_writer_removed_unexpected_total 1865
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5251
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47250
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4092
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 412
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46065
telemt_me_writer_teardown_success_total{mode="normal"} 52501
telemt_me_writer_teardown_noop_total 50574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103075
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.800063
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103075
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 585
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 1598
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8093502
telemt_user_connections_current{user="hello"} 5015
telemt_user_octets_from_client{user="hello"} 142733794257 (132.93 GB)
telemt_user_octets_to_client{user="hello"} 3120839507199 (2.84 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1972
telemt_user_unique_ips_recent_window{user="hello"} 779
```