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

# Server Metrics 2026-03-22 22:53:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 92834.3 (25h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3345611
telemt_connections_bad_total 264435
telemt_connections_current 861
telemt_connections_me_current 861
telemt_handshake_timeouts_total 105728
telemt_upstream_connect_attempt_total 34174
telemt_upstream_connect_success_total 34173
telemt_upstream_connect_attempts_per_request{bucket="1"} 34173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22266
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1350
telemt_me_reconnect_success_total 559
telemt_me_reader_eof_total 575
telemt_me_idle_close_by_peer_total 575
telemt_me_route_drop_no_conn_total 2964548
telemt_me_route_drop_channel_closed_total 1228
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2799638
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 636
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 722
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
telemt_me_writers_active_current 43
telemt_desync_total 11959
telemt_desync_full_logged_total 3749
telemt_desync_suppressed_total 8210
telemt_desync_frames_bucket_total{bucket="1_2"} 3228
telemt_desync_frames_bucket_total{bucket="3_10"} 4369
telemt_desync_frames_bucket_total{bucket="gt_10"} 4362
telemt_pool_swap_total 103
telemt_pool_force_close_total 3174
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 631
telemt_me_draining_writers_reap_progress_total 31256
telemt_me_writer_removed_unexpected_total 555
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2276
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29203
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3118
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28082
telemt_me_writer_teardown_success_total{mode="normal"} 31479
telemt_me_writer_teardown_noop_total 31267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62746
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 373.593825
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62746
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 631
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 498
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2788960
telemt_user_connections_current{user="hello"} 861
telemt_user_octets_from_client{user="hello"} 39934453708 (37.19 GB)
telemt_user_octets_to_client{user="hello"} 757140976464 (705.14 GB)
telemt_user_unique_ips_current{user="hello"} 367
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 106200.0 (29h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3955734
telemt_connections_bad_total 360603
telemt_connections_current 486
telemt_connections_me_current 486
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99891
telemt_upstream_connect_attempt_total 63884
telemt_upstream_connect_success_total 63103
telemt_upstream_connect_fail_total 691
telemt_upstream_connect_attempts_per_request{bucket="1"} 63794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28167
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 201
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 691
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9456
telemt_me_reconnect_success_total 3458
telemt_me_reader_eof_total 3475
telemt_me_idle_close_by_peer_total 3475
telemt_me_route_drop_no_conn_total 3635983
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3146274
telemt_me_endpoint_quarantine_total 786
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 820
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 12822
telemt_desync_full_logged_total 7189
telemt_desync_suppressed_total 5633
telemt_desync_frames_bucket_total{bucket="1_2"} 2897
telemt_desync_frames_bucket_total{bucket="3_10"} 5033
telemt_desync_frames_bucket_total{bucket="gt_10"} 4892
telemt_pool_swap_total 97
telemt_pool_force_close_total 2959
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 242
telemt_me_draining_writers_reap_progress_total 42649
telemt_me_writer_removed_unexpected_total 3411
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5823
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40264
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2501
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39690
telemt_me_writer_teardown_success_total{mode="normal"} 46087
telemt_me_writer_teardown_noop_total 42650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88737
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.513392
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88737
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 242
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 3127
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 258
telemt_user_connections_total{user="hello"} 3156913
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 42726323827 (39.79 GB)
telemt_user_octets_to_client{user="hello"} 780019563446 (726.45 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 181059.8 (50h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16223320
telemt_connections_bad_total 1615321
telemt_connections_current 1105
telemt_connections_me_current 1105
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396370
telemt_upstream_connect_attempt_total 80477
telemt_upstream_connect_success_total 80377
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 80394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38927
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1702
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2914
telemt_me_reconnect_success_total 1511
telemt_me_reader_eof_total 1456
telemt_me_idle_close_by_peer_total 1454
telemt_me_route_drop_no_conn_total 14032215
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12899544
telemt_me_endpoint_quarantine_total 1172
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1354
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_me_writers_active_current 48
telemt_desync_total 53338
telemt_desync_full_logged_total 16912
telemt_desync_suppressed_total 36426
telemt_desync_frames_bucket_total{bucket="1_2"} 11856
telemt_desync_frames_bucket_total{bucket="3_10"} 20766
telemt_desync_frames_bucket_total{bucket="gt_10"} 20716
telemt_pool_swap_total 196
telemt_pool_force_close_total 6509
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1046
telemt_me_draining_writers_reap_progress_total 60231
telemt_me_writer_removed_unexpected_total 1405
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5230
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55676
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6039
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53722
telemt_me_writer_teardown_success_total{mode="normal"} 60906
telemt_me_writer_teardown_noop_total 60284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 113733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 115486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121190
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 316.947618
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121190
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1046
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 1306
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 12899773
telemt_user_connections_current{user="hello"} 1105
telemt_user_octets_from_client{user="hello"} 190098665361 (177.04 GB)
telemt_user_octets_to_client{user="hello"} 3466240187631 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 526
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 181061.2 (50h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11776421
telemt_connections_bad_total 1212335
telemt_connections_current 819
telemt_connections_me_current 819
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344016
telemt_upstream_connect_attempt_total 94944
telemt_upstream_connect_success_total 93633
telemt_upstream_connect_fail_total 864
telemt_upstream_connect_attempts_per_request{bucket="1"} 94497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38922
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3795
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 864
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4331
telemt_me_reconnect_success_total 1820
telemt_me_reader_eof_total 1681
telemt_me_idle_close_by_peer_total 1681
telemt_me_route_drop_no_conn_total 4545143
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8754700
telemt_me_endpoint_quarantine_total 1181
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1375
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 38613
telemt_desync_full_logged_total 12991
telemt_desync_suppressed_total 25622
telemt_desync_frames_bucket_total{bucket="1_2"} 9540
telemt_desync_frames_bucket_total{bucket="3_10"} 14842
telemt_desync_frames_bucket_total{bucket="gt_10"} 14231
telemt_pool_swap_total 193
telemt_pool_force_close_total 5878
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 58574
telemt_me_writer_removed_unexpected_total 1716
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5352
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54789
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5366
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52696
telemt_me_writer_teardown_success_total{mode="normal"} 60141
telemt_me_writer_teardown_noop_total 58599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 117556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118740
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.267202
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118740
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1552
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8692524
telemt_user_connections_current{user="hello"} 819
telemt_user_octets_from_client{user="hello"} 217364376332 (202.44 GB)
telemt_user_octets_to_client{user="hello"} 3937847566799 (3.58 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 181025.3 (50h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10975469
telemt_connections_bad_total 957043
telemt_connections_current 388
telemt_connections_me_current 388
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345045
telemt_upstream_connect_attempt_total 79038
telemt_upstream_connect_success_total 77495
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 77700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37335
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5650
telemt_me_reconnect_success_total 2299
telemt_me_reader_eof_total 2039
telemt_me_idle_close_by_peer_total 2038
telemt_me_route_drop_no_conn_total 5327439
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8306058
telemt_me_endpoint_quarantine_total 1261
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1330
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
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
telemt_desync_total 37898
telemt_desync_full_logged_total 12567
telemt_desync_suppressed_total 25331
telemt_desync_frames_bucket_total{bucket="1_2"} 9570
telemt_desync_frames_bucket_total{bucket="3_10"} 14495
telemt_desync_frames_bucket_total{bucket="gt_10"} 13833
telemt_pool_swap_total 189
telemt_pool_force_close_total 5794
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 733
telemt_me_draining_writers_reap_progress_total 58784
telemt_me_writer_removed_unexpected_total 2193
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6071
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54834
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5223
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52990
telemt_me_writer_teardown_success_total{mode="normal"} 60905
telemt_me_writer_teardown_noop_total 58855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 113947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 116653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 117605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119760
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.619977
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119760
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 733
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 1990
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8298069
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 192220314907 (179.02 GB)
telemt_user_octets_to_client{user="hello"} 3451140542393 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 51305.2 (14h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11112232
telemt_connections_bad_total 667269
telemt_connections_current 1043
telemt_connections_me_current 1043
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 255609
telemt_upstream_connect_attempt_total 53371
telemt_upstream_connect_success_total 50596
telemt_upstream_connect_fail_total 1886
telemt_upstream_connect_attempts_per_request{bucket="1"} 52482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16845
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5999
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1886
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7287
telemt_me_reconnect_success_total 1109
telemt_me_reader_eof_total 681
telemt_me_idle_close_by_peer_total 680
telemt_me_route_drop_no_conn_total 25268667
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9229953
telemt_me_endpoint_quarantine_total 358
telemt_me_single_endpoint_outage_enter_total 84
telemt_me_single_endpoint_outage_exit_total 84
telemt_me_single_endpoint_outage_reconnect_attempt_total 157
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 157
telemt_me_single_endpoint_shadow_rotate_total 406
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
telemt_me_writers_active_current 44
telemt_desync_total 15888
telemt_desync_full_logged_total 4241
telemt_desync_suppressed_total 11647
telemt_desync_frames_bucket_total{bucket="1_2"} 3034
telemt_desync_frames_bucket_total{bucket="3_10"} 6422
telemt_desync_frames_bucket_total{bucket="gt_10"} 6432
telemt_pool_swap_total 52
telemt_pool_force_close_total 1792
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 462
telemt_me_draining_writers_reap_progress_total 15267
telemt_me_writer_removed_unexpected_total 999
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2203
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14015
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1485
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13475
telemt_me_writer_teardown_success_total{mode="normal"} 16218
telemt_me_writer_teardown_noop_total 15286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31504
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.673299
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31504
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 462
telemt_me_refill_failed_total 329
telemt_me_writer_restored_same_endpoint_total 714
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 9255465
telemt_user_connections_current{user="hello"} 1043
telemt_user_octets_from_client{user="hello"} 86105789238 (80.19 GB)
telemt_user_octets_to_client{user="hello"} 576395782449 (536.81 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 425
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 181031.7 (50h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10903789
telemt_connections_bad_total 927969
telemt_connections_current 756
telemt_connections_me_current 756
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 239580
telemt_upstream_connect_attempt_total 107795
telemt_upstream_connect_success_total 106669
telemt_upstream_connect_fail_total 954
telemt_upstream_connect_attempts_per_request{bucket="1"} 107623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1354
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 954
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72749
telemt_me_reconnect_success_total 2985
telemt_me_reader_eof_total 2679
telemt_me_idle_close_by_peer_total 2677
telemt_me_route_drop_no_conn_total 5247432
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8612354
telemt_me_endpoint_quarantine_total 1205
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1357
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
telemt_me_writers_active_current 41
telemt_desync_total 45985
telemt_desync_full_logged_total 15734
telemt_desync_suppressed_total 30251
telemt_desync_frames_bucket_total{bucket="1_2"} 9324
telemt_desync_frames_bucket_total{bucket="3_10"} 17600
telemt_desync_frames_bucket_total{bucket="gt_10"} 19061
telemt_pool_swap_total 185
telemt_pool_force_close_total 5483
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 655
telemt_me_draining_writers_reap_progress_total 62807
telemt_me_writer_removed_unexpected_total 2710
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6591
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58959
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4734
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57324
telemt_me_writer_teardown_success_total{mode="normal"} 65550
telemt_me_writer_teardown_noop_total 62808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 128348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128358
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.187122
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128358
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 655
telemt_me_refill_failed_total 4296
telemt_me_writer_restored_same_endpoint_total 2519
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8615432
telemt_user_connections_current{user="hello"} 756
telemt_user_octets_from_client{user="hello"} 193951919097 (180.63 GB)
telemt_user_octets_to_client{user="hello"} 3289519874212 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 376
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 117867.9 (32h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11578630
telemt_connections_bad_total 463149
telemt_connections_current 599
telemt_connections_me_current 599
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4744929
telemt_upstream_connect_attempt_total 55893
telemt_upstream_connect_success_total 55483
telemt_upstream_connect_fail_total 399
telemt_upstream_connect_attempts_per_request{bucket="1"} 55882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 399
telemt_me_reconnect_attempts_total 48724
telemt_me_reconnect_success_total 1741
telemt_me_reader_eof_total 1405
telemt_me_idle_close_by_peer_total 1404
telemt_me_route_drop_no_conn_total 4076183
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5567872
telemt_me_endpoint_quarantine_total 767
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 895
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31302
telemt_desync_full_logged_total 10656
telemt_desync_suppressed_total 20646
telemt_desync_frames_bucket_total{bucket="1_2"} 6212
telemt_desync_frames_bucket_total{bucket="3_10"} 12354
telemt_desync_frames_bucket_total{bucket="gt_10"} 12736
telemt_pool_swap_total 124
telemt_pool_force_close_total 3726
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 369
telemt_me_draining_writers_reap_progress_total 41840
telemt_me_writer_removed_unexpected_total 1459
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3562
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39777
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3285
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38114
telemt_me_writer_teardown_success_total{mode="normal"} 43339
telemt_me_writer_teardown_noop_total 41847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85186
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.637709
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85186
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 369
telemt_me_refill_failed_total 2730
telemt_me_writer_restored_same_endpoint_total 1545
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5560488
telemt_user_connections_current{user="hello"} 599
telemt_user_octets_from_client{user="hello"} 118674172812 (110.52 GB)
telemt_user_octets_to_client{user="hello"} 2150382975622 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 98839.1 (27h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1471298
telemt_connections_bad_total 36404
telemt_connections_current 490
telemt_connections_me_current 490
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29314
telemt_upstream_connect_attempt_total 46196
telemt_upstream_connect_success_total 46051
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 46168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20810
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 771
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2115
telemt_me_reconnect_success_total 867
telemt_me_reader_eof_total 846
telemt_me_idle_close_by_peer_total 846
telemt_me_route_drop_no_conn_total 507194
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1305938
telemt_me_endpoint_quarantine_total 797
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 813
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
telemt_me_writers_active_current 45
telemt_desync_total 8263
telemt_desync_full_logged_total 2493
telemt_desync_suppressed_total 5770
telemt_desync_frames_bucket_total{bucket="1_2"} 2080
telemt_desync_frames_bucket_total{bucket="3_10"} 3196
telemt_desync_frames_bucket_total{bucket="gt_10"} 2987
telemt_pool_swap_total 106
telemt_pool_force_close_total 2757
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 152
telemt_me_draining_writers_reap_progress_total 38759
telemt_me_writer_removed_unexpected_total 818
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3038
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36574
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2669
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36002
telemt_me_writer_teardown_success_total{mode="normal"} 39612
telemt_me_writer_teardown_noop_total 38763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78375
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.017724
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78375
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 152
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 735
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 1301825
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 25564914925 (23.81 GB)
telemt_user_octets_to_client{user="hello"} 556064428827 (517.88 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 181036.4 (50h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13227273
telemt_connections_bad_total 1570409
telemt_connections_current 755
telemt_connections_me_current 755
telemt_handshake_timeouts_total 380731
telemt_upstream_connect_attempt_total 69563
telemt_upstream_connect_success_total 69222
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 69427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34799
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2732
telemt_me_reconnect_success_total 1404
telemt_me_reader_eof_total 1380
telemt_me_idle_close_by_peer_total 1380
telemt_me_route_drop_no_conn_total 4473815
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9997359
telemt_me_endpoint_quarantine_total 1250
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1360
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 41775
telemt_desync_full_logged_total 13636
telemt_desync_suppressed_total 28139
telemt_desync_frames_bucket_total{bucket="1_2"} 10039
telemt_desync_frames_bucket_total{bucket="3_10"} 15368
telemt_desync_frames_bucket_total{bucket="gt_10"} 16368
telemt_pool_swap_total 201
telemt_pool_force_close_total 5440
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 664
telemt_me_draining_writers_reap_progress_total 62762
telemt_me_writer_removed_unexpected_total 1324
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5040
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59092
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5266
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57322
telemt_me_writer_teardown_success_total{mode="normal"} 64132
telemt_me_writer_teardown_noop_total 62764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 126896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 126896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 126896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 126896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 126896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 126896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 126896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 126896
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.619560
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 126896
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 664
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 1230
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 9964125
telemt_user_connections_current{user="hello"} 755
telemt_user_octets_from_client{user="hello"} 194219549988 (180.88 GB)
telemt_user_octets_to_client{user="hello"} 4417745417356 (4.02 TB)
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 181032.9 (50h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11523056
telemt_connections_bad_total 1317034
telemt_connections_current 656
telemt_connections_me_current 656
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 305971
telemt_upstream_connect_attempt_total 96139
telemt_upstream_connect_success_total 95281
telemt_upstream_connect_fail_total 651
telemt_upstream_connect_attempts_per_request{bucket="1"} 95932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 651
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10120
telemt_me_reconnect_success_total 2476
telemt_me_reader_eof_total 2304
telemt_me_idle_close_by_peer_total 2303
telemt_me_seq_mismatch_total 88
telemt_me_route_drop_no_conn_total 5634157
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8899819
telemt_me_endpoint_quarantine_total 1419
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 1362
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 41450
telemt_desync_full_logged_total 13299
telemt_desync_suppressed_total 28151
telemt_desync_frames_bucket_total{bucket="1_2"} 10663
telemt_desync_frames_bucket_total{bucket="3_10"} 15250
telemt_desync_frames_bucket_total{bucket="gt_10"} 15537
telemt_pool_swap_total 191
telemt_pool_force_close_total 5231
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 652
telemt_me_draining_writers_reap_progress_total 62602
telemt_me_writer_removed_unexpected_total 2341
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6393
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58630
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4760
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57371
telemt_me_writer_teardown_success_total{mode="normal"} 65023
telemt_me_writer_teardown_noop_total 62607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127630
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.331280
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127630
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 652
telemt_me_refill_failed_total 395
telemt_me_writer_restored_same_endpoint_total 2002
telemt_me_writer_restored_fallback_total 122
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 217
telemt_user_connections_total{user="hello"} 8905215
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 156916471513 (146.14 GB)
telemt_user_octets_to_client{user="hello"} 3466702488811 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 68
```