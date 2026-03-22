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

# Server Metrics 2026-03-22 23:59:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 96801.6 (26h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3428184
telemt_connections_bad_total 287274
telemt_connections_current 773
telemt_connections_me_current 773
telemt_handshake_timeouts_total 107604
telemt_upstream_connect_attempt_total 35773
telemt_upstream_connect_success_total 35772
telemt_upstream_connect_attempts_per_request{bucket="1"} 35772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23248
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1368
telemt_me_reconnect_success_total 577
telemt_me_reader_eof_total 593
telemt_me_idle_close_by_peer_total 593
telemt_me_route_drop_no_conn_total 2973627
telemt_me_route_drop_channel_closed_total 1230
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2847354
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 669
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 753
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
telemt_desync_total 12224
telemt_desync_full_logged_total 3830
telemt_desync_suppressed_total 8394
telemt_desync_frames_bucket_total{bucket="1_2"} 3310
telemt_desync_frames_bucket_total{bucket="3_10"} 4449
telemt_desync_frames_bucket_total{bucket="gt_10"} 4465
telemt_pool_swap_total 107
telemt_pool_force_close_total 3324
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 646
telemt_me_draining_writers_reap_progress_total 32770
telemt_me_writer_removed_unexpected_total 572
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2382
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30607
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3268
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29446
telemt_me_writer_teardown_success_total{mode="normal"} 32989
telemt_me_writer_teardown_noop_total 32781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65770
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 375.330701
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65770
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 646
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 515
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2836598
telemt_user_connections_current{user="hello"} 773
telemt_user_octets_from_client{user="hello"} 40698453516 (37.90 GB)
telemt_user_octets_to_client{user="hello"} 775736261872 (722.46 GB)
telemt_user_unique_ips_current{user="hello"} 364
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 110168.0 (30h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3977227
telemt_connections_bad_total 362368
telemt_connections_current 167
telemt_connections_me_current 167
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100297
telemt_upstream_connect_attempt_total 68139
telemt_upstream_connect_success_total 67317
telemt_upstream_connect_fail_total 729
telemt_upstream_connect_attempts_per_request{bucket="1"} 68046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 729
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9798
telemt_me_reconnect_success_total 3542
telemt_me_reader_eof_total 3546
telemt_me_idle_close_by_peer_total 3546
telemt_me_route_drop_no_conn_total 3638762
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3163153
telemt_me_endpoint_quarantine_total 852
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 857
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 12914
telemt_desync_full_logged_total 7236
telemt_desync_suppressed_total 5678
telemt_desync_frames_bucket_total{bucket="1_2"} 2932
telemt_desync_frames_bucket_total{bucket="3_10"} 5062
telemt_desync_frames_bucket_total{bucket="gt_10"} 4920
telemt_pool_swap_total 102
telemt_pool_force_close_total 3014
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 245
telemt_me_draining_writers_reap_progress_total 44780
telemt_me_writer_removed_unexpected_total 3480
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6022
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42267
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2556
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41766
telemt_me_writer_teardown_success_total{mode="normal"} 48289
telemt_me_writer_teardown_noop_total 44781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93070
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.558849
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93070
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 245
telemt_me_refill_failed_total 240
telemt_me_writer_restored_same_endpoint_total 3180
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 3175634
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 42896781586 (39.95 GB)
telemt_user_octets_to_client{user="hello"} 787812176792 (733.71 GB)
telemt_user_msgs_from_client{user="hello"} 47428
telemt_user_msgs_to_client{user="hello"} 180951
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 185028.0 (51h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16287839
telemt_connections_bad_total 1639654
telemt_connections_current 853
telemt_connections_me_current 853
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396767
telemt_upstream_connect_attempt_total 82546
telemt_upstream_connect_success_total 82443
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 82460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40177
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1709
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2961
telemt_me_reconnect_success_total 1539
telemt_me_reader_eof_total 1486
telemt_me_idle_close_by_peer_total 1484
telemt_me_route_drop_no_conn_total 14039601
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12938209
telemt_me_endpoint_quarantine_total 1213
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1389
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
telemt_desync_total 53581
telemt_desync_full_logged_total 17000
telemt_desync_suppressed_total 36581
telemt_desync_frames_bucket_total{bucket="1_2"} 11929
telemt_desync_frames_bucket_total{bucket="3_10"} 20891
telemt_desync_frames_bucket_total{bucket="gt_10"} 20761
telemt_pool_swap_total 200
telemt_pool_force_close_total 6623
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1055
telemt_me_draining_writers_reap_progress_total 62169
telemt_me_writer_removed_unexpected_total 1432
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5349
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57525
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6153
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55546
telemt_me_writer_teardown_success_total{mode="normal"} 62874
telemt_me_writer_teardown_noop_total 62222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125096
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.533466
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125096
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1055
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1331
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 12938274
telemt_user_connections_current{user="hello"} 853
telemt_user_octets_from_client{user="hello"} 190836788773 (177.73 GB)
telemt_user_octets_to_client{user="hello"} 3480559448999 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 185029.2 (51h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11828638
telemt_connections_bad_total 1222913
telemt_connections_current 681
telemt_connections_me_current 681
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344366
telemt_upstream_connect_attempt_total 96944
telemt_upstream_connect_success_total 95630
telemt_upstream_connect_fail_total 865
telemt_upstream_connect_attempts_per_request{bucket="1"} 96495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40072
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3798
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 865
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4358
telemt_me_reconnect_success_total 1845
telemt_me_reader_eof_total 1710
telemt_me_idle_close_by_peer_total 1710
telemt_me_route_drop_no_conn_total 4550238
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8786624
telemt_me_endpoint_quarantine_total 1219
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1410
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
telemt_me_writers_active_current 44
telemt_desync_total 38656
telemt_desync_full_logged_total 13011
telemt_desync_suppressed_total 25645
telemt_desync_frames_bucket_total{bucket="1_2"} 9563
telemt_desync_frames_bucket_total{bucket="3_10"} 14851
telemt_desync_frames_bucket_total{bucket="gt_10"} 14242
telemt_pool_swap_total 197
telemt_pool_force_close_total 5982
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 707
telemt_me_draining_writers_reap_progress_total 60435
telemt_me_writer_removed_unexpected_total 1741
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5464
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56567
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5470
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54453
telemt_me_writer_teardown_success_total{mode="normal"} 62031
telemt_me_writer_teardown_noop_total 60460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 115749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122491
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.374566
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122491
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 707
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1576
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 8724416
telemt_user_connections_current{user="hello"} 681
telemt_user_octets_from_client{user="hello"} 217627320236 (202.68 GB)
telemt_user_octets_to_client{user="hello"} 3949612171243 (3.59 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 184993.2 (51h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11017091
telemt_connections_bad_total 967062
telemt_connections_current 435
telemt_connections_me_current 435
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345303
telemt_upstream_connect_attempt_total 81184
telemt_upstream_connect_success_total 79630
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 79835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38507
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2018
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5693
telemt_me_reconnect_success_total 2337
telemt_me_reader_eof_total 2079
telemt_me_idle_close_by_peer_total 2078
telemt_me_route_drop_no_conn_total 5332419
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8332975
telemt_me_endpoint_quarantine_total 1294
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1366
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
telemt_me_writers_active_current 44
telemt_desync_total 37977
telemt_desync_full_logged_total 12592
telemt_desync_suppressed_total 25385
telemt_desync_frames_bucket_total{bucket="1_2"} 9595
telemt_desync_frames_bucket_total{bucket="3_10"} 14521
telemt_desync_frames_bucket_total{bucket="gt_10"} 13861
telemt_pool_swap_total 193
telemt_pool_force_close_total 5883
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 737
telemt_me_draining_writers_reap_progress_total 60754
telemt_me_writer_removed_unexpected_total 2231
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6210
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56705
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5312
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54871
telemt_me_writer_teardown_success_total{mode="normal"} 62915
telemt_me_writer_teardown_noop_total 60825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123740
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.669912
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123740
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 737
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 2028
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8324954
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 192514533239 (179.29 GB)
telemt_user_octets_to_client{user="hello"} 3460286039897 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 55272.9 (15h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11176184
telemt_connections_bad_total 668088
telemt_connections_current 953
telemt_connections_me_current 953
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 263720
telemt_upstream_connect_attempt_total 55236
telemt_upstream_connect_success_total 52395
telemt_upstream_connect_fail_total 1901
telemt_upstream_connect_attempts_per_request{bucket="1"} 54296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6003
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1901
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7461
telemt_me_reconnect_success_total 1156
telemt_me_reader_eof_total 731
telemt_me_idle_close_by_peer_total 730
telemt_me_route_drop_no_conn_total 25278110
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9282626
telemt_me_endpoint_quarantine_total 400
telemt_me_single_endpoint_outage_enter_total 85
telemt_me_single_endpoint_outage_exit_total 85
telemt_me_single_endpoint_outage_reconnect_attempt_total 158
telemt_me_single_endpoint_outage_reconnect_success_total 42
telemt_me_single_endpoint_quarantine_bypass_total 158
telemt_me_single_endpoint_shadow_rotate_total 437
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
telemt_desync_total 16227
telemt_desync_full_logged_total 4395
telemt_desync_suppressed_total 11832
telemt_desync_frames_bucket_total{bucket="1_2"} 3081
telemt_desync_frames_bucket_total{bucket="3_10"} 6586
telemt_desync_frames_bucket_total{bucket="gt_10"} 6560
telemt_pool_swap_total 57
telemt_pool_force_close_total 1914
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 472
telemt_me_draining_writers_reap_progress_total 16909
telemt_me_writer_removed_unexpected_total 1047
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2336
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15561
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1607
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14995
telemt_me_writer_teardown_success_total{mode="normal"} 17897
telemt_me_writer_teardown_noop_total 16928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34825
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.541123
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34825
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 472
telemt_me_refill_failed_total 336
telemt_me_writer_restored_same_endpoint_total 753
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 9308081
telemt_user_connections_current{user="hello"} 953
telemt_user_octets_from_client{user="hello"} 86521207018 (80.58 GB)
telemt_user_octets_to_client{user="hello"} 595313704581 (554.43 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 398
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 184999.4 (51h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10954136
telemt_connections_bad_total 941969
telemt_connections_current 705
telemt_connections_me_current 705
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 241672
telemt_upstream_connect_attempt_total 110063
telemt_upstream_connect_success_total 108926
telemt_upstream_connect_fail_total 965
telemt_upstream_connect_attempts_per_request{bucket="1"} 109891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1356
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 965
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72819
telemt_me_reconnect_success_total 3027
telemt_me_reader_eof_total 2719
telemt_me_idle_close_by_peer_total 2717
telemt_me_route_drop_no_conn_total 5255269
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8644779
telemt_me_endpoint_quarantine_total 1232
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1395
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
telemt_me_writers_active_current 47
telemt_desync_total 46114
telemt_desync_full_logged_total 15784
telemt_desync_suppressed_total 30330
telemt_desync_frames_bucket_total{bucket="1_2"} 9369
telemt_desync_frames_bucket_total{bucket="3_10"} 17653
telemt_desync_frames_bucket_total{bucket="gt_10"} 19092
telemt_pool_swap_total 189
telemt_pool_force_close_total 5585
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 64884
telemt_me_writer_removed_unexpected_total 2750
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6711
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60956
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4836
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59299
telemt_me_writer_teardown_success_total{mode="normal"} 67667
telemt_me_writer_teardown_noop_total 64885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 132545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 132548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 132552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 132552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 132552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 132552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 132552
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.215431
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 132552
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2558
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8647824
telemt_user_connections_current{user="hello"} 705
telemt_user_octets_from_client{user="hello"} 194243001157 (180.90 GB)
telemt_user_octets_to_client{user="hello"} 3301002033428 (3.00 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 121835.7 (33h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11648796
telemt_connections_bad_total 476247
telemt_connections_current 497
telemt_connections_me_current 497
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4759216
telemt_upstream_connect_attempt_total 58207
telemt_upstream_connect_success_total 57783
telemt_upstream_connect_fail_total 413
telemt_upstream_connect_attempts_per_request{bucket="1"} 58196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 413
telemt_me_reconnect_attempts_total 48822
telemt_me_reconnect_success_total 1770
telemt_me_reader_eof_total 1441
telemt_me_idle_close_by_peer_total 1440
telemt_me_route_drop_no_conn_total 4081758
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5595585
telemt_me_endpoint_quarantine_total 817
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 932
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
telemt_me_writers_active_current 42
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31466
telemt_desync_full_logged_total 10721
telemt_desync_suppressed_total 20745
telemt_desync_frames_bucket_total{bucket="1_2"} 6265
telemt_desync_frames_bucket_total{bucket="3_10"} 12411
telemt_desync_frames_bucket_total{bucket="gt_10"} 12790
telemt_pool_swap_total 129
telemt_pool_force_close_total 3823
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 43994
telemt_me_writer_removed_unexpected_total 1492
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3681
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41848
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3382
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40171
telemt_me_writer_teardown_success_total{mode="normal"} 45529
telemt_me_writer_teardown_noop_total 44001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89530
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.675013
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89530
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 2734
telemt_me_writer_restored_same_endpoint_total 1572
telemt_me_writer_restored_fallback_total 23
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5588160
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 118893403624 (110.73 GB)
telemt_user_octets_to_client{user="hello"} 2162744652790 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 102806.3 (28h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1497750
telemt_connections_bad_total 36641
telemt_connections_current 421
telemt_connections_me_current 421
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29949
telemt_upstream_connect_attempt_total 48107
telemt_upstream_connect_success_total 47955
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 48079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 782
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2167
telemt_me_reconnect_success_total 884
telemt_me_reader_eof_total 865
telemt_me_idle_close_by_peer_total 865
telemt_me_route_drop_no_conn_total 513315
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1330379
telemt_me_endpoint_quarantine_total 836
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 846
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
telemt_me_writers_active_current 44
telemt_desync_total 8618
telemt_desync_full_logged_total 2559
telemt_desync_suppressed_total 6059
telemt_desync_frames_bucket_total{bucket="1_2"} 2301
telemt_desync_frames_bucket_total{bucket="3_10"} 3311
telemt_desync_frames_bucket_total{bucket="gt_10"} 3006
telemt_pool_swap_total 111
telemt_pool_force_close_total 2870
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 160
telemt_me_draining_writers_reap_progress_total 40524
telemt_me_writer_removed_unexpected_total 836
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3159
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38237
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2782
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37654
telemt_me_writer_teardown_success_total{mode="normal"} 41396
telemt_me_writer_teardown_noop_total 40528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81924
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.159858
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81924
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 160
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 749
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 1326219
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 25790367581 (24.02 GB)
telemt_user_octets_to_client{user="hello"} 570196453011 (531.04 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 185004.3 (51h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13282195
telemt_connections_bad_total 1588084
telemt_connections_current 638
telemt_connections_me_current 638
telemt_handshake_timeouts_total 386519
telemt_upstream_connect_attempt_total 71922
telemt_upstream_connect_success_total 71577
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 71786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36046
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2891
telemt_me_reconnect_success_total 1442
telemt_me_reader_eof_total 1425
telemt_me_idle_close_by_peer_total 1425
telemt_me_route_drop_no_conn_total 4478820
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10022586
telemt_me_endpoint_quarantine_total 1290
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1396
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
telemt_me_writers_active_current 44
telemt_desync_total 41896
telemt_desync_full_logged_total 13679
telemt_desync_suppressed_total 28217
telemt_desync_frames_bucket_total{bucket="1_2"} 10090
telemt_desync_frames_bucket_total{bucket="3_10"} 15404
telemt_desync_frames_bucket_total{bucket="gt_10"} 16402
telemt_pool_swap_total 205
telemt_pool_force_close_total 5520
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 673
telemt_me_draining_writers_reap_progress_total 64963
telemt_me_writer_removed_unexpected_total 1365
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5167
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 61211
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5346
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59443
telemt_me_writer_teardown_success_total{mode="normal"} 66378
telemt_me_writer_teardown_noop_total 64965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 130834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 131210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 131330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 131343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 131343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 131343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 131343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 131343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 131343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 131343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 131343
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.739202
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 131343
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 673
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1264
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 9989319
telemt_user_connections_current{user="hello"} 638
telemt_user_octets_from_client{user="hello"} 194432453340 (181.08 GB)
telemt_user_octets_to_client{user="hello"} 4431741433288 (4.03 TB)
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 185000.7 (51h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11577135
telemt_connections_bad_total 1334779
telemt_connections_current 504
telemt_connections_me_current 504
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 309321
telemt_upstream_connect_attempt_total 98642
telemt_upstream_connect_success_total 97766
telemt_upstream_connect_fail_total 667
telemt_upstream_connect_attempts_per_request{bucket="1"} 98433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41665
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 667
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10323
telemt_me_reconnect_success_total 2535
telemt_me_reader_eof_total 2354
telemt_me_idle_close_by_peer_total 2353
telemt_me_seq_mismatch_total 93
telemt_me_route_drop_no_conn_total 5639157
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8928703
telemt_me_endpoint_quarantine_total 1472
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 1399
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
telemt_me_writers_active_current 45
telemt_desync_total 41653
telemt_desync_full_logged_total 13380
telemt_desync_suppressed_total 28273
telemt_desync_frames_bucket_total{bucket="1_2"} 10745
telemt_desync_frames_bucket_total{bucket="3_10"} 15307
telemt_desync_frames_bucket_total{bucket="gt_10"} 15601
telemt_pool_swap_total 195
telemt_pool_force_close_total 5313
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 64950
telemt_me_writer_removed_unexpected_total 2393
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6532
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 60894
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4842
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 59637
telemt_me_writer_teardown_success_total{mode="normal"} 67426
telemt_me_writer_teardown_noop_total 64955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 132331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 132381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 132381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 132381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 132381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 132381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 132381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 132381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 132381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 132381
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.436780
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 132381
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 403
telemt_me_writer_restored_same_endpoint_total 2047
telemt_me_writer_restored_fallback_total 128
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 8934043
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 157120225749 (146.33 GB)
telemt_user_octets_to_client{user="hello"} 3476483464155 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 252
telemt_user_unique_ips_recent_window{user="hello"} 54
```